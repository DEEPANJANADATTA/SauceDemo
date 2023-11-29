# SauceDemo
Sample Test Case
 @Test(priority = 1)
  public void Log_in() {
	  
	  
	  driver.manage().window().maximize();
	  driver.get("https://www.saucedemo.com/");
	  driver.findElement(By.id("user-name")).sendKeys("standard_user");
	  driver.findElement(By.id("password")).sendKeys("secret_sauce");
	  driver.findElement(By.id("login-button")).click();
	  
  }
