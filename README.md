Smart Assign IT is a browser-based IT ticket routing tool built for Pleasants Companies LLC.
It streamlines the process of assigning incoming Alloy helpdesk tickets to the appropriate IT technician by automating the decision-making process 
that would otherwise rely on manual judgment. The app accepts a pasted Alloy ticket row along with an optional client summary and location, then scores 
each technician against a library of 31 job categories using keyword matching, recency of prior work, and seniority. Hard override rules handle high-priority
routing cases like phishing emails, printer issues, Reline tickets, QuickBooks updates, and terminations. Client location is treated as the top priority in
all recommendations. The technician roster includes seven staff members across Clarksburg, Frederick NHQ, and Frederick Paving locations, with rotating techs
able to be manually placed at any site. An Out of Office toggle removes unavailable techs from recommendations entirely. Selecting a technician generates a formatted
output string ready to paste into Alloy and copies it to the clipboard automatically. A child ticket suggestion feature detects new hire and foreman setup tickets
and automatically recommends sub-tasks for phone/iPad setup (James) and laptop ordering and configuration. The app runs entirely in the browser with no dependencies
or internet connection required beyond the logo image. Schedule and workload data persist via localStorage. 
Future development includes a Node.js backend to automate ticket ingestion from the Alloy API and post recommendations directly to a Slack channel.
