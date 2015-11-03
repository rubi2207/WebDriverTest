package Example;

import org.openqa.selenium.WebDriver;
import org.openqa.selenium.firefox.FirefoxDriver;
import org.testng.Assert;
import org.testng.annotations.AfterTest;
import org.testng.annotations.BeforeTest;
import org.testng.annotations.Test;

public class NewTest {

	private WebDriver driver;

	@BeforeTest
	public void beforeTest() {
		driver = new FirefoxDriver();
	}

	@Test
	public void testEasy() {
		driver.get("http://www.guru99.com/selenium-tutorial.html");
		String title = driver.getTitle();
		Assert.assertTrue(title.contains("Free Selenium Tutorials"));
		System.out.println("Hi");
	}

	@AfterTest
	public void afterTest() {
		driver.quit();
	}

}
