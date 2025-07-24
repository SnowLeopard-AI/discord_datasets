[![Discord](https://img.shields.io/discord/1379929746875617413?logo=discord&logoColor=white)](https://discord.gg/WGAyr8NpEX)

# Stack Overflow Dataset

This dataset contains comprehensive Stack Overflow content from the world's largest online community for programmers to learn, share their knowledge, and advance their careers. Updated on a quarterly basis, this BigQuery dataset includes an archive of Stack Overflow content, including posts, votes, tags, and badges.

This public dataset is hosted in [Google BigQuery]([url](https://cloud.google.com/bigquery)) and is included in BigQuery's 1TB/mo of free tier processing. The dataset is updated to mirror the Stack Overflow content on the Internet Archive, and is also available through the Stack Exchange Data Explorer.

For convenience, we have included the first 100 rows of each dataset in [data_tops](https://github.com/SnowLeopard-AI/discord_datasets/tree/main/stack-overflow/data_tops). You can also query the full dataset directly using [BigQuery's free tier](https://console.cloud.google.com/marketplace/product/stack-exchange/stack-overflow). 

## Dataset Overview

The Stack Overflow dataset includes the following tables:

### Posts and Content
- `posts_answers` - Answer posts
- `posts_questions` - Question posts
- `posts_moderator_nomination` - Moderator nomination posts
- `posts_orphaned_tag_wiki` - Orphaned tag wiki content
- `posts_privilege_wiki` - Privilege wiki content
- `posts_tag_wiki` - Tag wiki pages
- `posts_tag_wiki_excerpt` - Tag wiki excerpts
- `posts_wiki_placeholder` - Wiki placeholder content
- `stackoverflow_posts` - Combined posts table

### Post Metadata and Relationships
- `post_history` - Edit history and revisions of posts
- `post_links` - Relationships and links between posts

### User Interactions
- `comments` - Comments on posts
- `votes` - Upvotes and downvotes on posts

### Users and Organization
- `users` - User profiles, reputation scores, and activity metrics
- `tags` - Topic tags associated with questions and their usage statistics

### Additional Tables
- `badges` - Achievement badges earned by users for various contributions

## Getting Started

1. Join [Snow Leopard's Discord server](https://discord.gg/WGAyr8NpEX)
2. Enter the `stack-overflow` channel to ask snowy about the Stack Overflow datasets
3. Ask your programming and Stack Overflow-related questions!

🤔 Not sure what to ask? Here are a few sample questions.

### Questions and Answers
```
@snowy, what percentage of questions have been answered over the years?
```
```
@snowy, which day of the week has most questions answered within an hour?
```
```
@snowy, what are the most popular programming languages discussed on Stack Overflow?
```

### Users and Reputation
```
@snowy, what is the reputation and badge count of users across different tenures on Stack Overflow?
```
```
@snowy, who are the top contributors by reputation score?
```
```
@snowy, how does user activity change over time on Stack Overflow?
```

### Tags and Topics
```
@snowy, what are the most popular tags on Stack Overflow?
```
```
@snowy, how have programming language trends changed over time?
```
```
@snowy, which tags have the highest answer rates?
```

### Badges and Achievements
```
@snowy, what are the 10 "easier" gold badges to earn?
```
```
@snowy, which badges are most commonly earned by new users?
```
```
@snowy, how long does it take on average to earn different badge types?
```
