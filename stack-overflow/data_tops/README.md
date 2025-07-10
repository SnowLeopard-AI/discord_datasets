[![Discord](https://img.shields.io/discord/1379929746875617413?logo=discord&logoColor=white)](https://discord.gg/WGAyr8NpEX)

# Stack Overflow Dataset Tops

These are the first 100 rows of each dataset from the Stack Overflow BigQuery public dataset.

More information about the dataset can be found in the [main Stack Overflow README](https://github.com/SnowLeopard-AI/discord_datasets/tree/main/stack-overflow).

## Stack Overflow Dataset Schemas

### badges
| Field | Type | Mode | Description |
|-------|------|------|-------------|
| id | INTEGER | NULLABLE | Badge identifier |
| name | STRING | NULLABLE | Name of the badge |
| date | TIMESTAMP | NULLABLE | Date when the badge was awarded |
| user_id | INTEGER | NULLABLE | ID of the user who earned the badge |
| class | INTEGER | NULLABLE | Badge class/type |
| tag_based | BOOLEAN | NULLABLE | Whether the badge is tag-based |

### post_history
| Field | Type | Mode | Description |
|-------|------|------|-------------|
| id | INTEGER | NULLABLE | Post history entry identifier |
| creation_date | TIMESTAMP | NULLABLE | Date when the edit was made |
| post_id | INTEGER | NULLABLE | ID of the post that was edited |
| post_history_type_id | INTEGER | NULLABLE | Type of edit/change made |
| revision_guid | STRING | NULLABLE | Unique identifier for the revision |
| user_id | INTEGER | NULLABLE | ID of the user who made the edit |
| text | STRING | NULLABLE | Content of the edit |
| comment | STRING | NULLABLE | Edit comment/summary |

### post_links
| Field | Type | Mode | Description |
|-------|------|------|-------------|
| id | INTEGER | NULLABLE | Post link identifier |
| creation_date | TIMESTAMP | NULLABLE | Date when the link was created |
| link_type_id | INTEGER | NULLABLE | Type of link relationship |
| post_id | INTEGER | NULLABLE | ID of the source post |
| related_post_id | INTEGER | NULLABLE | ID of the related/linked post |

### posts_answers
| Field | Type | Mode | Description |
|-------|------|------|-------------|
| id | INTEGER | NULLABLE | Answer post identifier |
| title | STRING | NULLABLE | Title of the post |
| body | STRING | NULLABLE | Content/body of the answer |
| accepted_answer_id | STRING | NULLABLE | ID of the accepted answer (if applicable) |
| answer_count | STRING | NULLABLE | Number of answers to the question |
| comment_count | INTEGER | NULLABLE | Number of comments on the post |
| community_owned_date | TIMESTAMP | NULLABLE | Date when post became community-owned |
| creation_date | TIMESTAMP | NULLABLE | Date when the answer was created |
| favorite_count | STRING | NULLABLE | Number of times favorited |
| last_activity_date | TIMESTAMP | NULLABLE | Date of last activity on the post |
| last_edit_date | TIMESTAMP | NULLABLE | Date of last edit |
| last_editor_display_name | STRING | NULLABLE | Display name of last editor |
| last_editor_user_id | INTEGER | NULLABLE | User ID of last editor |
| owner_display_name | STRING | NULLABLE | Display name of the post owner |
| owner_user_id | INTEGER | NULLABLE | User ID of the post owner |
| parent_id | INTEGER | NULLABLE | ID of the parent question |
| post_type_id | INTEGER | NULLABLE | Type of post (answer = 2) |
| score | INTEGER | NULLABLE | Score/votes for the answer |
| tags | STRING | NULLABLE | Tags associated with the post |
| view_count | STRING | NULLABLE | Number of views |

### posts_moderator_nomination
| Field | Type | Mode | Description |
|-------|------|------|-------------|
| id | INTEGER | NULLABLE | Moderator nomination post identifier |
| title | STRING | NULLABLE | Title of the nomination post |
| body | STRING | NULLABLE | Content/body of the nomination |
| accepted_answer_id | STRING | NULLABLE | ID of the accepted answer (if applicable) |
| answer_count | STRING | NULLABLE | Number of answers |
| comment_count | INTEGER | NULLABLE | Number of comments on the post |
| community_owned_date | TIMESTAMP | NULLABLE | Date when post became community-owned |
| creation_date | TIMESTAMP | NULLABLE | Date when the nomination was created |
| favorite_count | STRING | NULLABLE | Number of times favorited |
| last_activity_date | TIMESTAMP | NULLABLE | Date of last activity on the post |
| last_edit_date | TIMESTAMP | NULLABLE | Date of last edit |
| last_editor_display_name | STRING | NULLABLE | Display name of last editor |
| last_editor_user_id | INTEGER | NULLABLE | User ID of last editor |
| owner_display_name | STRING | NULLABLE | Display name of the nominee |
| owner_user_id | INTEGER | NULLABLE | User ID of the nominee |
| parent_id | STRING | NULLABLE | ID of the parent post |
| post_type_id | INTEGER | NULLABLE | Type of post (moderator nomination) |
| score | INTEGER | NULLABLE | Score/votes for the nomination |
| tags | STRING | NULLABLE | Tags associated with the post |
| view_count | STRING | NULLABLE | Number of views |

### posts_orphaned_tag_wiki
| Field | Type | Mode | Description |
|-------|------|------|-------------|
| id | INTEGER | NULLABLE | Orphaned tag wiki post identifier |
| title | STRING | NULLABLE | Title of the tag wiki post |
| body | STRING | NULLABLE | Content/body of the tag wiki |
| accepted_answer_id | STRING | NULLABLE | ID of the accepted answer (if applicable) |
| answer_count | STRING | NULLABLE | Number of answers |
| comment_count | INTEGER | NULLABLE | Number of comments on the post |
| community_owned_date | TIMESTAMP | NULLABLE | Date when post became community-owned |
| creation_date | TIMESTAMP | NULLABLE | Date when the tag wiki was created |
| favorite_count | STRING | NULLABLE | Number of times favorited |
| last_activity_date | TIMESTAMP | NULLABLE | Date of last activity on the post |
| last_edit_date | TIMESTAMP | NULLABLE | Date of last edit |
| last_editor_display_name | STRING | NULLABLE | Display name of last editor |
| last_editor_user_id | INTEGER | NULLABLE | User ID of last editor |
| owner_display_name | STRING | NULLABLE | Display name of the post owner |
| owner_user_id | INTEGER | NULLABLE | User ID of the post owner |
| parent_id | STRING | NULLABLE | ID of the parent post |
| post_type_id | INTEGER | NULLABLE | Type of post (orphaned tag wiki) |
| score | INTEGER | NULLABLE | Score/votes for the post |
| tags | STRING | NULLABLE | Tags associated with the post |
| view_count | STRING | NULLABLE | Number of views |

### posts_privilege_wiki
| Field | Type | Mode | Description |
|-------|------|------|-------------|
| id | INTEGER | NULLABLE | Privilege wiki post identifier |
| title | STRING | NULLABLE | Title of the privilege wiki post |
| body | STRING | NULLABLE | Content/body of the privilege wiki |
| accepted_answer_id | STRING | NULLABLE | ID of the accepted answer (if applicable) |
| answer_count | STRING | NULLABLE | Number of answers |
| comment_count | INTEGER | NULLABLE | Number of comments on the post |
| community_owned_date | STRING | NULLABLE | Date when post became community-owned |
| creation_date | TIMESTAMP | NULLABLE | Date when the privilege wiki was created |
| favorite_count | STRING | NULLABLE | Number of times favorited |
| last_activity_date | TIMESTAMP | NULLABLE | Date of last activity on the post |
| last_edit_date | TIMESTAMP | NULLABLE | Date of last edit |
| last_editor_display_name | STRING | NULLABLE | Display name of last editor |
| last_editor_user_id | INTEGER | NULLABLE | User ID of last editor |
| owner_display_name | STRING | NULLABLE | Display name of the post owner |
| owner_user_id | INTEGER | NULLABLE | User ID of the post owner |
| parent_id | STRING | NULLABLE | ID of the parent post |
| post_type_id | INTEGER | NULLABLE | Type of post (privilege wiki) |
| score | INTEGER | NULLABLE | Score/votes for the post |
| tags | STRING | NULLABLE | Tags associated with the post |
| view_count | STRING | NULLABLE | Number of views |

### posts_questions
| Field | Type | Mode | Description |
|-------|------|------|-------------|
| id | INTEGER | NULLABLE | Question post identifier |
| title | STRING | NULLABLE | Title of the question |
| body | STRING | NULLABLE | Content/body of the question |
| accepted_answer_id | INTEGER | NULLABLE | ID of the accepted answer |
| answer_count | INTEGER | NULLABLE | Number of answers to the question |
| comment_count | INTEGER | NULLABLE | Number of comments on the post |
| community_owned_date | TIMESTAMP | NULLABLE | Date when post became community-owned |
| creation_date | TIMESTAMP | NULLABLE | Date when the question was created |
| favorite_count | INTEGER | NULLABLE | Number of times favorited |
| last_activity_date | TIMESTAMP | NULLABLE | Date of last activity on the post |
| last_edit_date | TIMESTAMP | NULLABLE | Date of last edit |
| last_editor_display_name | STRING | NULLABLE | Display name of last editor |
| last_editor_user_id | INTEGER | NULLABLE | User ID of last editor |
| owner_display_name | STRING | NULLABLE | Display name of the question author |
| owner_user_id | INTEGER | NULLABLE | User ID of the question author |
| parent_id | STRING | NULLABLE | ID of the parent post |
| post_type_id | INTEGER | NULLABLE | Type of post (question = 1) |
| score | INTEGER | NULLABLE | Score/votes for the question |
| tags | STRING | NULLABLE | Tags associated with the question |
| view_count | INTEGER | NULLABLE | Number of views |

### posts_tag_wiki
| Field | Type | Mode | Description |
|-------|------|------|-------------|
| id | INTEGER | NULLABLE | Tag wiki post identifier |
| title | STRING | NULLABLE | Title of the tag wiki post |
| body | STRING | NULLABLE | Content/body of the tag wiki |
| accepted_answer_id | STRING | NULLABLE | ID of the accepted answer (if applicable) |
| answer_count | STRING | NULLABLE | Number of answers |
| comment_count | INTEGER | NULLABLE | Number of comments on the post |
| community_owned_date | TIMESTAMP | NULLABLE | Date when post became community-owned |
| creation_date | TIMESTAMP | NULLABLE | Date when the tag wiki was created |
| favorite_count | STRING | NULLABLE | Number of times favorited |
| last_activity_date | TIMESTAMP | NULLABLE | Date of last activity on the post |
| last_edit_date | TIMESTAMP | NULLABLE | Date of last edit |
| last_editor_display_name | STRING | NULLABLE | Display name of last editor |
| last_editor_user_id | INTEGER | NULLABLE | User ID of last editor |
| owner_display_name | STRING | NULLABLE | Display name of the post owner |
| owner_user_id | INTEGER | NULLABLE | User ID of the post owner |
| parent_id | STRING | NULLABLE | ID of the parent post |
| post_type_id | INTEGER | NULLABLE | Type of post (tag wiki) |
| score | INTEGER | NULLABLE | Score/votes for the post |
| tags | STRING | NULLABLE | Tags associated with the post |
| view_count | STRING | NULLABLE | Number of views |

### posts_tag_wiki_excerpt
| Field | Type | Mode | Description |
|-------|------|------|-------------|
| id | INTEGER | NULLABLE | Tag wiki excerpt post identifier |
| title | STRING | NULLABLE | Title of the tag wiki excerpt post |
| body | STRING | NULLABLE | Content/body of the tag wiki excerpt |
| accepted_answer_id | STRING | NULLABLE | ID of the accepted answer (if applicable) |
| answer_count | STRING | NULLABLE | Number of answers |
| comment_count | INTEGER | NULLABLE | Number of comments on the post |
| community_owned_date | TIMESTAMP | NULLABLE | Date when post became community-owned |
| creation_date | TIMESTAMP | NULLABLE | Date when the tag wiki excerpt was created |
| favorite_count | STRING | NULLABLE | Number of times favorited |
| last_activity_date | TIMESTAMP | NULLABLE | Date of last activity on the post |
| last_edit_date | TIMESTAMP | NULLABLE | Date of last edit |
| last_editor_display_name | STRING | NULLABLE | Display name of last editor |
| last_editor_user_id | INTEGER | NULLABLE | User ID of last editor |
| owner_display_name | STRING | NULLABLE | Display name of the post owner |
| owner_user_id | INTEGER | NULLABLE | User ID of the post owner |
| parent_id | STRING | NULLABLE | ID of the parent post |
| post_type_id | INTEGER | NULLABLE | Type of post (tag wiki excerpt) |
| score | INTEGER | NULLABLE | Score/votes for the post |
| tags | STRING | NULLABLE | Tags associated with the post |
| view_count | STRING | NULLABLE | Number of views |

### posts_wiki_placeholder
| Field | Type | Mode | Description |
|-------|------|------|-------------|
| id | INTEGER | NULLABLE | Wiki placeholder post identifier |
| title | STRING | NULLABLE | Title of the wiki placeholder post |
| body | STRING | NULLABLE | Content/body of the wiki placeholder |
| accepted_answer_id | STRING | NULLABLE | ID of the accepted answer (if applicable) |
| answer_count | STRING | NULLABLE | Number of answers |
| comment_count | INTEGER | NULLABLE | Number of comments on the post |
| community_owned_date | STRING | NULLABLE | Date when post became community-owned |
| creation_date | TIMESTAMP | NULLABLE | Date when the wiki placeholder was created |
| favorite_count | STRING | NULLABLE | Number of times favorited |
| last_activity_date | TIMESTAMP | NULLABLE | Date of last activity on the post |
| last_edit_date | TIMESTAMP | NULLABLE | Date of last edit |
| last_editor_display_name | STRING | NULLABLE | Display name of last editor |
| last_editor_user_id | INTEGER | NULLABLE | User ID of last editor |
| owner_display_name | STRING | NULLABLE | Display name of the post owner |
| owner_user_id | INTEGER | NULLABLE | User ID of the post owner |
| parent_id | STRING | NULLABLE | ID of the parent post |
| post_type_id | INTEGER | NULLABLE | Type of post (wiki placeholder) |
| score | INTEGER | NULLABLE | Score/votes for the post |
| tags | STRING | NULLABLE | Tags associated with the post |
| view_count | STRING | NULLABLE | Number of views |

### stackoverflow_posts
| Field | Type | Mode | Description |
|-------|------|------|-------------|
| id | INTEGER | REQUIRED | Post identifier (primary key) |
| title | STRING | NULLABLE | Title of the post |
| body | STRING | NULLABLE | Content/body of the post |
| accepted_answer_id | INTEGER | NULLABLE | ID of the accepted answer |
| answer_count | INTEGER | NULLABLE | Number of answers to the post |
| comment_count | INTEGER | NULLABLE | Number of comments on the post |
| community_owned_date | TIMESTAMP | NULLABLE | Date when post became community-owned |
| creation_date | TIMESTAMP | NULLABLE | Date when the post was created |
| favorite_count | INTEGER | NULLABLE | Number of times favorited |
| last_activity_date | TIMESTAMP | NULLABLE | Date of last activity on the post |
| last_edit_date | TIMESTAMP | NULLABLE | Date of last edit |
| last_editor_display_name | STRING | NULLABLE | Display name of last editor |
| last_editor_user_id | INTEGER | NULLABLE | User ID of last editor |
| owner_display_name | STRING | NULLABLE | Display name of the post owner |
| owner_user_id | INTEGER | NULLABLE | User ID of the post owner |
| parent_id | INTEGER | NULLABLE | ID of the parent post |
| post_type_id | INTEGER | NULLABLE | Type of post (1=question, 2=answer) |
| score | INTEGER | NULLABLE | Score/votes for the post |
| tags | STRING | NULLABLE | Tags associated with the post |
| view_count | INTEGER | NULLABLE | Number of views |

### tags
| Field | Type | Mode | Description |
|-------|------|------|-------------|
| id | INTEGER | NULLABLE | Tag identifier |
| tag_name | STRING | NULLABLE | Name of the tag |
| count | INTEGER | NULLABLE | Number of times the tag has been used |
| excerpt_post_id | INTEGER | NULLABLE | ID of the tag excerpt post |
| wiki_post_id | INTEGER | NULLABLE | ID of the tag wiki post |

### users
| Field | Type | Mode | Description |
|-------|------|------|-------------|
| id | INTEGER | NULLABLE | User identifier |
| display_name | STRING | NULLABLE | Display name of the user |
| about_me | STRING | NULLABLE | User's about me section |
| age | STRING | NULLABLE | User's age |
| creation_date | TIMESTAMP | NULLABLE | Date when the user account was created |
| last_access_date | TIMESTAMP | NULLABLE | Date of user's last access |
| location | STRING | NULLABLE | User's location |
| reputation | INTEGER | NULLABLE | User's reputation score |
| up_votes | INTEGER | NULLABLE | Number of upvotes the user has given |
| down_votes | INTEGER | NULLABLE | Number of downvotes the user has given |
| views | INTEGER | NULLABLE | Number of profile views |
| profile_image_url | STRING | NULLABLE | URL to user's profile image |
| website_url | STRING | NULLABLE | User's website URL |

### votes
| Field | Type | Mode | Description |
|-------|------|------|-------------|
| id | INTEGER | NULLABLE | Vote identifier |
| creation_date | TIMESTAMP | NULLABLE | Date when the vote was cast |
| post_id | INTEGER | NULLABLE | ID of the post that was voted on |
| vote_type_id | INTEGER | NULLABLE | Type of vote (upvote, downvote, etc.) |