# Analysis of GitHub Users in the city of Sydney with over 100 followers
<ul>
  <li><h2>Data Scraping :</h2>
  I defined a GitHubScraper class that interacts with the GitHub API to collect user information and their repositories. I used libraries such as Requests for making HTTP requests and Pandas for data storage. The scraped user data and repository data are stored in files (users.csv and repositories.csv) using pandas.</li>
  <li><h2>Most Surprising Fact :</h2>
  <h5>Correlation Between Followers and Public Repositories: 0.035</h5>
This indicates a weak positive correlation, suggesting that increasing number of repositories is unlikely to lead to increase in followers. 
      <h5>Regression Slope of Followers on Repositories: 0.068</h5>
This specifies that for each additional public repository, number of followers is expected to increase by approximately 0.068 followers.
  </li>
  <li><h2>Recommendations for developers :</h2>
    <ol>
      <li>Prioritize the quality of repositories over quantity. Create well-documented, valuable projects that solve real problems or contribute to community</li>
      <li>Utilize GitHub's features like GitHub Pages, README files, and project boards to showcase your work effectively. This facilitate a better understanding for users, leading to greater interest and more followers.</li>
    </ol>
  </li>
</ul>
       <h2>Other Interesting Facts:</h2>
<ol>
  <li>Despite JavaScript being the most popular programming language among users in Sydney, it is noteworthy that Mermaid exhibited the highest average number of stars per repository.</li>
  <li>In the city of Sydney, there are 376 users with more than 100 followers.</li>
</ol>
