from selenium import webdriver
from selenium.webdriver.common.keys import Keys

browser = webdriver.Chrome()

#print("Enter a keyword to search on shodan.io: ", end='')

keyword = 'webcam'

browser.get('https://www.shodan.io/')

elem = browser.find_element_by_id('search_input') 

elem.send_keys(keyword + Keys.RETURN)

#browser.quit()
