# newformtesting

# code

```
from selenium import webdriver
from selenium.webdriver.common.by import By

import time

driver = webdriver.Chrome()

driver.get("https://vinothqaacademy.com/demo-site/")

time.sleep(5)

f_name = driver.find_element(By.ID,"vfb-5")
f_name.send_keys("Thirumalai")

l_name= driver.find_element(By.ID,"vfb-7")
l_name.send_keys("Vengadesan")

Male = driver.find_element(By.NAME,"vfb-31")

Male.click()
print("radio function worked")

course = driver.find_element(By.ID,"vfb-20-0")
course.click()

print("course filled")

address=driver.find_element(By.ID,"vfb-13-address")
address.send_keys("57/435 ,Pillayar Kovil Street")

address2 = driver.find_element(By.ID,"vfb-13-address-2")
address2.send_keys("Uthangarai (Tk) ,Krishnagiri(Dt)")

code = driver.find_element(By.ID,"vfb-13-zip")
code.send_keys("635307")

email = driver.find_element(By.ID,"vfb-14")
email.send_keys("thirumalaiofficial007@gmail.com")
print("All details filled")

state = driver.find_element(By.CLASS_NAME,"select2-selection__arrow")
state.click()

country = driver.find_element(By.CLASS_NAME,"select2-search__field")
country.send_keys("India")

time.sleep(10)
```

# image

<img width="1737" height="577" alt="image" src="https://github.com/user-attachments/assets/7f3f0a27-2c09-49d3-981b-ada18484c2d7" />
