# hackathon #1 - let's build an SMS-burner-service
At this hackathon we're building an SMS-burner web-service.

## Materials provided
* Raspberry PI Zero W (Preloaded with Raspbian)
* +5V 4A and adjustable (1-11V) 4A power sources
* SIM800L GSM Module
* Prepaid sim-card
* Linux-based cloud VPS (Clean Ubuntu 16.04 installed)
* Wi-Fi (Raspberry Pi's already configured)
* Beer, softdrinks and snacks

## Teams
Form teams of 4-5 people and try to solve the entire objective on your own. If you get stuck, ask other teams and the organizer for help. Help other teams.

## Scoring/Rules/Goals
Negative:

| Score | Description |
| --- | --- |
| -100 | New SMS messages doesn't show up on web page |
| -100 | Phone number is not displayed on web page |
| -50 | SMS device sends data unencrypted |
| -50 | SMS device doesn't authenticate |
| -20 | Code repo contains credentials |
| -20 | Presented data on webpage not sanitized |

Bonus:

| Score | Description |
| --- | --- |
| +20 | Code checked into public repo |
| +10 | New messages show up without reloading page |
| +10 | The service has a blacklist of offensive words which removes offensive messages |
| +10 | Code has unit-test with good coverage |
| +10 | Website is "all green" on [Webbkoll](https://webbkoll.dataskydd.net/) |
| +5 | The service has a A+ SSL score on [SSL Labs test](https://www.ssllabs.com/ssltest/) |
| +5 | The service uses rate limiting to limit abuse |




