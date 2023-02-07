# Slips

## Improvement of Slips web interface
- Better Display of timewindow numbers,  start time, and end time
- Showing all the info we have on each profile.
- Show a list of Blocked Profiles in one place
- Show the history of threat levels and confidence of each profile
- If an IPv4 profile has an available IPv6 we should show it. and vice versa
- Show the current threat level of each profile 
- Show the user agent of each profile 
- Show the MAC of each profile
- Live (Asynchronous) updating of the web view. (meaning that without refreshing the page, new info should be displayed)
- Show slips logo somewhere
- Showing about a profile
- Progress bar if possible
- List of loaded modules and disabled modules
- Show current model status (are we in training or testing mode)
- Show the current gateway’s IP and MAC, an mark the gateway profile as ‘Gateway’
- Have a whitelist tab to show what IPs/domains/orgs are currently whitelisted
- Manage the configuration of slips from the web
	- Change the feeds : JA3 feeds, SSL feeds, TI feeds
	- Whitelist
	- Manage API keys: VT, riskIQ, slack bot token
	- Warden.conf
	- Slips.conf
	- Local TI files

## Better Installation

- An easy way to install slips, Any of the following:
  - using apt
  - snap
  - dpkg
  
- Bonus: brew installation of slips (if the student has a macOS)  

## Improve Performance

- CPU Profiling; Using python profilers: for example profile and cProfile modules or others
- Memory Profiling; Using memray, Memory Profiler module or others that may do
- Provide statistics and graphs about which parts or modules of slips need optimizations
- Provide optimization ideas; what can be done differently? Why and How?


--- 

# AIP