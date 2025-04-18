from rich.console import Console
from rich import print
from rich.panel import Panel
import os
import time
import pyfiglet
import requests
import random

# Session-----Conslone-----INSTALL....
ses = requests.Session()
console = Console()

#-----package  TARMUX -----#
packages = [
    "termux-setup-storage", "pkg update", "pkg upgrade", "pkg install python", "pkg install python2",
    "pkg install python3", "pkg install python-pip", "pkg install wget", "pkg install fish", "pkg install ruby",
    "pkg install help", "pkg install git", "pkg install dnsutils", "pkg install php", "pkg install perl", 
    "pkg install lua", "pkg install parallel", "pkg install nmap", "pkg install bash", "pkg install clang",
    "pkg install nano", "pkg install w3m", "pkg install hydra", "pkg install figlet", "pkg install cowsay", 
    "pkg install curl", "pkg install tar", "pkg install zip", "pkg install unzip", "pkg install net-tools",
    "pkg install tor", "pkg install sudo", "pkg install wireshark", "pkg install wgetrc", "pkg install wcalc", 
    "pkg install openssl", "pkg install openssl-tool", "pkg install bmon", "pkg install vpn", "pkg install unrar",
    "pkg install toilet", "pkg install proot", "pkg install vim", "pkg install vim-python", "pkg install ired", 
    "pkg install goaccess", "pkg install golang", "pkg install kibi", "pkg install tsu", "pkg install tmux", 
    "pkg install mtools", "pkg install file", "pkg install pass", "pkg install pick", "pkg install chroot", 
    "termux-chroot", "pkg install macchanger", "pkg install ninja", "pkg install elixir", "pkg install swift", 
    "pkg install xmlstarlet", "pkg install fakeroot", "pkg install texinfo", "pkg install netcat", "pkg install wren", 
    "pkg install gatling", "pkg install cvs", "pkg install ffmpeg", "pkg install screen", "pkg install neofetch", 
    "pkg install mariadb", "pkg install picolisp", "pkg install cmatrix", "pkg install dropbear", "pkg install openssh", 
    "pkg install python-pip", "pip2 install wget", "pip install bs4", "pip2 install bs4", "pip install requests", 
    "pip2 install requests", "pip install mechanize", "pip2 install mechanize", "pip install php", "pip2 install php"
]

#--------Colour CODE------#
A = "\033[30;1;28m" 
B = "\033[30;1;50m"
C = "\033[30;1;105m"
D = "\033[30;1;46m"
E = "\033[30;1;15m"
F = "\033[30;1;265m"
G = "\033[30;1;226m"
I = "\033[30;1;123m"
J = "\033[30;1;160m"
K = "\033[30;1;81m"
L = "\033[1;34m"

#-----------------------#EMOJI system-------#
X = "[©]"
V = """
     "[bold bright_red💔]💚[/] [bold yellow]💯[/] [bold red]❤️‍🩹[/] "
    "[bold magenta]🤩[/] [bold orange]🧡[/] [bold blue]💙[/] "
    "[bold purple]💜[/] [bold black] 🖤 [/] [bold white] 🤍?[/] "
    "[bold bright_red]💔?[/] [bold bright_red💔]🥷?[/] "
"""
#--------def clear --------#
def clear():
    print("Jone MY Channel's 🥷🖤️🥷")
    os.system('espeak -a 100 " jone, my Teligerm channel "')
    os.system("xdg-open https://t.me/RS_CYBER_X_Halp_com")
    os.system("xdg-open https://t.me/RS_CYBER_X_Halp_com")
    os.system("xdg-open https://github.com/RS-RAIHAN")
    os.system("xdg-open https://www.facebook.com/RS.CYBER.KING")
    print(" install modeul just w8...😁 ")
    os.system('espeak -a 100 " install ,  module just white"')
    os.system("pip install rich pyfiglet requests")
    os.system('pkg install espeak')
    os.system('clear')

#----------LOGO------RS-RAIHAN------#
logo_text = "RAIHAN"
ascii_logo = pyfiglet.figlet_format(logo_text)

def speak(message):
    os.system(f'espeak -a 100 "{message}"')

#------------MENU MAIN
def main():
    clear()
    print(f"[bold cyan]{ascii_logo}[/bold cyan]")
    console.print("[bold bright_blue]DEVELOPER :[/] [bold bright_red💔]RS-RAIHAN[/] [yellow]••[/]")
    console.print("[bold bright_red] TOOL : TARMUX SETUP[/] [yellow]★★[/]")
    console.print("[bold bright_red💔] TELEGRAM : https://t.me/RS_CYBER_X_Halp_com[/] [yellow]→→★[/]")
    console.print("[bold bright_red💔] VERSION : 0.1[/] [yellow]‍≠≈[/]")
    console.print(V)
    
    speak("Welcome to Tarmux setup. Choose an option.")
    console.print(f"[bold bright_red💔]1.[/bold bright_red💔] [cyan]TERMUX SETUP[/cyan]")
    option = input(f"{X} CHOICE : ")
    
    if option == "1":
        speak("Starting Termux setup.")
        mix_x()
    elif option == "2":
        speak("Calling owner feature coming soon!")
        console.print(f"[yellow]Calling Owner...[/yellow] [cyan](Feature coming soon!)[/cyan]")
        os.system("xdg-open hhttps://www.facebook.com/RS.CYBER.KING")
        time.sleep(2)
    else:
        speak("Please select a correct option.")
        print(f"{J}{X} PLEASE SELECT CORRECTLY !!")
        time.sleep(2)
        main()

def mix_x():
    clear()
    for package in packages:  # LOOP------INSTALLl----PACES
        speak(f"Installing {package}")
        print(f"[bold cyan]{ascii_logo}[/bold cyan]")
        print(f"[bold cyan]Installing {package}...[/bold cyan]")
        os.system(package)
        
        #EMOJI______INSTALL-------#
        print(f"[bold bright_red💔]✅ {package} installed successfully![/bold bright_red💔] {random.choice(['🔥', '💯', '🎉', '🌟'])}")
        time.sleep(1)  # 1-----Packeecs download of review emjoi-------#
    
    speak("All packages installed successfully!")
    print("[bold bright_red💔]All packages installed successfully![/bold bright_red💔] 🎉🎉")
    time.sleep(2)
    main()

main()
