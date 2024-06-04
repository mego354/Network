# CS50’s Web Programming with Python and JavaScript - Project 4: Network

This project is a Twitter-like social network website for making posts and following users.

## Technologies Used
- Django
- JavaScript
- HTML
- CSS

## Features

### New Post
- **Authenticated users** can write and submit a new text-based post.
- The "New Post" box can be displayed at the top of the "All Posts" page or on a separate page.

### All Posts
- The "All Posts" page displays posts from all users in reverse chronological order.
- Each post includes:
  - Username of the poster
  - Post content
  - Date and time of posting
  - Number of likes

### Profile Page
- Clicking on a username loads that user's profile page.
- The profile page displays:
  - Number of followers
  - Number of users the profile user follows
  - All posts from the user in reverse chronological order
- For other users, the profile page shows a "Follow" or "Unfollow" button.
  - Users cannot follow themselves.

### Following
- The "Following" page shows posts from users that the current user follows.
- This page functions like the "All Posts" page but is limited to followed users.
- Available only to authenticated users.

### Pagination
- Posts are displayed 10 per page.
- "Next" and "Previous" buttons are available for navigation through pages of posts.

### Edit Post
- Users can edit their own posts.
- Clicking "Edit" replaces the post content with a textarea for editing.
- Users can save the edited post without reloading the page using JavaScript.
- Users cannot edit others' posts for security.

### Like and Unlike
- Users can toggle "like" on any post.
- The like count updates asynchronously using JavaScript without reloading the page.

[Demo Video](https://youtu.be/qVGaknkC7K8?si=pNzGlvarm0PUXv36)

For more details on the project specifications, visit [CS50 Network Project](https://cs50.harvard.edu/web/2020/projects/4/network/).
