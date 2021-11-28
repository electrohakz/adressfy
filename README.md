# adressfy
Program that can find website domains if it's .com
print ('wecome to adressyfy')

print('find web urls')

web=input('enter the web site you need to find url: ')

web_url=web+'.com'

print(web_url)

no_more=input('no more??? y/n:')

while no_more=='y':

    web=input('enter the web site youneed to find url: ')

    web_url=web+'.com'

    print(web_url)

    no_more=input('no more??? y/n:')

if no_more=='n':

    print('exit')
