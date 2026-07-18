<h3>Traffic Analysis for ClubRunner websites — solving the multi-domain analytics challenge</h3>
ClubRunner's multi-domain architecture is a secure design for data integrity: member data is isolated from the public website by running on separate domains, admin on another domain, and so on.<br/>
For traffic analytics, this design however gives quite a few challenges. Out of the box, Google Analytics (GA4) treats navigation between these domains as referral traffic. Standard GA4 thus gives you inflated session counts, and little insight into what members actually do on your site.<br/>
We've put together a GTM + GA4 configuration that addresses this and also adds features for more data. <br/><br/>
The support page on <a href="https://rotary2405.se/page/support-trafikanalys">Traffic Analysis</a> (use translation buttons at the top of the page) explains why measurement and configuration are needed.
