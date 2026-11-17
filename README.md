This is a Streamlit web app built by Randy Singh of Kalsnet (KNet) Consulting Group. It recreates the Microsoft 365 outage 
of 12–14 November 2026, when Exchange Online failures spread to Teams, SharePoint, Copilot, Defender and Power Platform. 
A region-by-region simulator steps through the outage in 5-minute intervals and follows the cause Microsoft  described: 
a configuration change cut each server's capacity to set up secure (TLS) connections, slower servers failed their health checks 
and were removed, and the remaining servers took on their traffic and failed in turn. 
