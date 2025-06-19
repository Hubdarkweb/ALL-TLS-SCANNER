TOpPLUG-Hunters
# **INSTALLATION**
READ EVERYTHING TO UNDERSTAND 

TOpPLUG HUNTER🕷🐼
   ## Hello 👋

<h1 align="center">ꪶ🐼🕷TOpPLUG🕷🐼-Hunterꫂ<br></h1>
<p align="center">
<img src="https://i.imgur.com/Gw7jtD0.jpeg, https://i.imgur.com/nB8i4tq.jpeg" />
</p>
<h1 align="center">ꪶ🐼🕷TOpPLUG🕷🐼-Hunterꫂ<br></h1>
<p align="center">
<img src="https://i.imgur.com/or4X9rl.jpeg,https://i.imgur.com/hoRK15o.jpeg" />
</p>
<h1 align="center">ꪶ🐼🕷TOpPLUG🕷🐼-Hunterꫂ<br></h1>
<p align="center">
<img src="https://i.imgur.com/tqP6Vsl.jpeg, https://i.imgur.com/Sfzusgg.jpeg" />
</p>
<h1 align="center">ꪶ🐼🕷TOpPLUG🔫🗽🏴‍☠️🎳-Hunterꫂ<br></h1>
<p align="center">
<img src="https://i.imgur.com/nB8i4tq.jpeg" />
</p>
<h1 align="center">ꪶ🐼🕷TOpPLUG🥷✈️🛸-Hunterꫂ<br></h1>
<p align="center">
<img src="https://i.imgur.com/hoRK15o.jpeg" />
</p>
<h1 align="center">ꪶ🐼🕷TOpPLUG🧑‍💻-Hunterꫂ⛷️🛫<br></h1>
<p align="center">
<img src="https://i.imgur.com/tqP6Vsl.jpeg, https://i.imgur.com/Sfzusgg.jpeg" />
</p>
<h1 align="center">ꪶ🐼🕷TOpPLUG🤿🛰️📡🧑‍💻-Hunterꫂ<br></h1>
<p align="center">
<img src="https://i.imgur.com/Sfzusgg.jpeg" />
</p>
<p align="center">
🐼🕷TOpPLUG🕷🐼 Hunter Multiscanner <a href="https://github.com/Hubdarkweb" target="_blank">TOpPLUG</a> using <a href="https://github.com" target="_blank">TOpPLUG</a> and <a href="https://github.com/python" target="_blank">python</a>. Dont forget to give a star bro.
</p>
<p align="center">
  <a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=EB+Garamond&weight=800&size=28&duration=4000&pause=1000&random=false&width=435&lines=+_____🐼🕷TOpPLUG🕷🐼_____;HOST+UNLIMITED+x+HUNTER+BOT;DEVELOPED+BY+🐼🕷TOpPLUG🕷🐼;REALESE+DATE+4%2F9%2F2024." alt="Typing SVG" /></a>
</p>

# TOpPLUG-Hunters Terminal installation 
# TERMUX INSTALLATION MANUAL 
how to scan using TOpPLUG-hunter
**»»install the following on termux:**

Proxy Tester

A Python script to test HTTP proxy connectivity to a list of hosts using HTTP CONNECT requests. The script supports command-line arguments for specifying the proxy and hosts, as well as interactive input for flexibility. It logs results based on HTTP status codes (200, 429, 502) and provides a colorful console interface with a progress spinner.

Features





Concurrent Testing: Test multiple hosts concurrently using a configurable number of threads.



Command-Line Support: Specify proxy and hosts via command-line arguments (-proxy and -f).



Interactive Mode: Prompt for hosts and thread count if not provided via command line.



Logging: Save results to log files (success_200.log, too_many_requests_429.log, bad_gateway_502.log).



Colorful Output: Uses colorama and pystyle for a visually appealing console experience.



Progress Tracking: Displays a real-time progress spinner with percentage completion.

Prerequisites





Python 3.x



Required packages:





colorama



pystyle



A working HTTP proxy server



A list of target hosts (domains or IPs) in a file or as comma-separated values

Installation





Clone or download the repository:
````
git clone https://github.com/Hubdarkweb/ALL-TLS-SCANNER.git
cd Hubdarkweb

````

Install dependencies:
````
pip install colorama pystyle

````

Ensure the script (any-tls.py) is in your working directory.

Usage

Run the script using command-line arguments or in interactive mode.

Command-Line Mode
````
python any-tls.py [-proxy <host:port>] [-f <file_or_domains>]
````
Options





-proxy <host:port>: Specify the proxy server (e.g., 157.83.8.0:8080). Default: 157.240.195.32:8080.



-f <file_or_domains>: Path to a file with hosts (one per line) or comma-separated domains (e.g., google.com,youtube.com).

Examples





Test hosts from a file with a specific proxy:
````
python any-tls.py -proxy 157.83.8.0:8080 -f hosts.txt

````

Test specific domains with the default proxy:
````
python any-tls -f google.com,youtube.com
````


Use default proxy and prompt for hosts:

python any-tls

Interactive Mode

If -f is not provided, the script prompts for:





Number of threads (default: 10)



Hosts (comma-separated domains or path to a file)

Example Interaction

Enter number of threads (default 10):
> 5
Enter domain(s) (comma separated) or path to a file:
Examples: google.com,youtube.com OR hosts.txt
> google.com,youtube.com

Hosts File Format

Create a file (e.g., hosts.txt) with one host per line. Empty lines are ignored.

Example hosts.txt:

google.com
youtube.com
example.com

Output





Console: Displays a banner, test results (HTTP 200, 429, 502), response times, and truncated responses. A progress spinner shows the number of hosts processed.



Log Files:





success_200.log: Hosts with HTTP 200 responses.



too_many_requests_429.log: Hosts with HTTP 429 responses.



bad_gateway_502.log: Hosts with HTTP 502 responses.

Example Console Output:

[google.com] - HTTP 200
✓ HTTP 200 response (0.32s)
Response: HTTP/1.1 200 OK...
----------------------------------------
Progress: ⬤ 1/2 (50.0%)

Notes





Timeout: Each connection attempt has a 15-second timeout.



Response Size: Responses are limited to 4096 bytes per chunk, with console output truncated to 500 characters.



Proxy: Ensure the proxy server is accessible before running the script.



Permissions: Ensure write permissions in the working directory for log files.

Troubleshooting





Syntax Errors: Verify the script matches the latest version (check for typos like ward).



File Not Found: Ensure the hosts file exists and is accessible (use full path if needed).



Connection Issues: Test the proxy with tools like curl --proxy <host:port> https://google.com.



Termux Users: Ensure directory permissions with chmod +w ..

Author





Developed by: TOpPLUG



GitHub: https://github.com/Hubdarkweb



Discord: https://discord.gg/Hub7s

License

This project is licensed under the MIT License.
