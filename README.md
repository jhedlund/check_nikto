# check_nikto
This Nagios plugin monitors a domain in search of web vulnerabilities, so it uses the scan of Web Nikto vulnerabilities, producing an HTML report, and alerting to the existence of known vulnerabilities, returning the critical state in case of detection. The domain to be monitored is passed as an argument, and can optionally be specified the port of communication, the board where the report will be stored, the name, and the validity time of the report, as well as the types of vulnerabilities to be searched. NB: The execution of this plugin is only possible with the installation of the scan of web vulnerabilities Nikto
