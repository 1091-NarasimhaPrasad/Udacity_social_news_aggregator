                                                    Udiddit-A-social-news-aggregator

Build the supporting data structure for Udiddit (similar to Reddit), a social media news aggregator site. Design a new, normalized and performant database and migrate over data from the previously poorly designed database.

Project Introduction: Udiddit, A Social News Aggregator

Udiddit is a social news aggregator, content rating, and discussions website. On Udiddit, registered users are able to link to external content or post their own text content about various topics, ranging from common topics such as photography and food, to more arcane ones such as horse masks or birds with arms. In turn, other users can comment on these posts, and each user is allowed to cast a vote about each post, either in an up (like) or down (dislike) direction.

Unfortunately, due to some time constraints before the initial launch of the site, the data model stored in Postgres hasn’t been well thought out, and is starting to show its flaws. I’ve been brought in for two reasons: first, to make an assessment of the situation and take steps to fix all the issues with the current data model, and then, once successful, to improve the current system by making it more robust and adding some web analytics.
