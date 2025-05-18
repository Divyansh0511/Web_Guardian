# Web Guardian is a web vulnerability assesment tool that focuses on automating the prosess of finding bugs on a website 

$ go run WebGuardian.go                               

██╗    ██╗███████╗██████╗  ██████╗ ██╗   ██╗ █████╗ ██████╗ ██████╗ ██╗ █████╗ ███╗   ██╗
██║    ██║██╔════╝██╔══██╗██╔════╝ ██║   ██║██╔══██╗██╔══██╗██╔══██╗██║██╔══██╗████╗  ██║
██║ █╗ ██║█████╗  ██████╔╝██║  ███╗██║   ██║███████║██████╔╝██║  ██║██║███████║██╔██╗ ██║
██║███╗██║██╔══╝  ██╔══██╗██║   ██║██║   ██║██╔══██║██╔══██╗██║  ██║██║██╔══██║██║╚██╗██║
╚███╔███╔╝███████╗██████╔╝╚██████╔╝╚██████╔╝██║  ██║██║  ██║██████╔╝██║██║  ██║██║ ╚████║
 ╚══╝╚══╝ ╚══════╝╚═════╝  ╚═════╝  ╚═════╝ ╚═╝  ╚═╝╚═╝  ╚═╝╚═════╝ ╚═╝╚═╝  ╚═╝╚═╝  ╚═══╝  
                          Automated Web Security Sentinel Suite

    Contributer:
    Singh Divya Madan:        https://github.com/Divya-03s
    Yuvraj Singh Gohil:       https://github.com/yuvrajgohil24
    Kanishk Malav:            https://github.com/Kanishk-Malav
    Taukir Ahmed:             https://github.com/Technoob09
    Divyansh Jha:             https://github.com/Divyansh0511
   
    Flags:
    -domain       Specify the target domain (required)
    -basic        Run Basic Information Gathering
    -dorking      Run Google Dorking
    -subdomains   Run Subdomain Enumeration
    -crawling     Run Web Crawling on Alive Subdomain
    -vuln         Run Vulnerability Discovery
    -full         Run Full Scan (basic info, dorking, subdomain enumeration, vulnerability discovery)
    -h            Print this help manual

    Example Usage:
    webguardian -basic -domain example.com
    webguardian -dorking -domain example.com
    webguardian -subdomains -domain example.com
    webguardian -crawling -domain example.com
    webguardian -vuln -domain example.com
    webguardian -full -domain example.com
    webguardian -h
                                                            
