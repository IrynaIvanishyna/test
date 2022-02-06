from selenium import webdriver
driver = webdriver.Firefox()
driver.get('https://www.youtube.com/')
searchbox = driver.find_element_by_xpath('//*[@id="search"]')
