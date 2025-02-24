# Cricket_Score_Notification
<p>
  <h2>Overview</h2>
This project is a Python-based script that scrapes live cricket scores from Google and sends desktop notifications to keep you updated on the latest match scores. It continuously checks for live scores of a specified cricket team and alerts you via notifications.
</p>

<p>
  <h2>Features</h2>
Live Score Scraping: The script scrapes live cricket scores from Google search results for a specified team.
Notifications: Sends desktop notifications every 10 seconds, displaying the current score and summary of the ongoing match.
Real-time Updates: Continuously fetches updated scores, ensuring you're always informed about the latest game progress.

</p>


<h2>Requirements</h2>
<p>Make sure you have the following Python libraries installed:</p>

<ul>
  <li>requests: To make HTTP requests and fetch page content.</li>
  <li>beautifulsoup4: To parse the HTML page and extract the necessary information.</li>
  <li>plyer: To send desktop notifications.</li>
</ul>








<h1>How It Works</h1>
<ol>
  <li>The get_score() function:</li>
  <ul>
    <li>Accepts the name of a cricket team as input.</li>
    <li>Uses requests to send a query to Google Search for live scores of the team.</li>
    <li>Scrapes the results using BeautifulSoup, extracting relevant score details, teams, and summaries.</li>
  </ul>
  <li>Desktop Notification:</li>
  <ul>
    <li>Once the score is scraped, a desktop notification is triggered using the plyer library to alert you of the current score and match status.</li>
  </ul>
  <li>The script runs continuously, fetching live score data for the specified team at regular intervals (every 10 seconds).</li>
</ol>
