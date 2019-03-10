# Resurrector
Our official submission for **Microsoft CodeFunDo++ 2018**, in which we stood among the top 20 teams in our institute.

We created a `natural disaster management` *WebApp* using **Django**, which will bring better connectivity to a calamity hit area providing volunteer help and updating about any impending danger.

- Our application runs on two modes : **Victim** and **Volunteer** mode. One can get an account in either of them.
- SMS alerts to victims in the area with directions to the nearest relief centre, using **Twilio Rest Client**.
- Used **Google Maps API**, for automated suggestions of health-care centres and police stations to triage relief from, and for heat-map generation.
- Used **Microsoft Cognitive Face API** , for facial recognition, to hand out relief. Photos of victims to be taken at the centre. Facial recognition will determine if relief has already been handed out to a particular individual at the centre. The families can also search for their relatives by merely uploading their photos.
- **Twitter Stream data analysis** to coordinate response and relief, using Twitter Search API
