   glue = {"steps"},
public interface AutomationMain {

String getDriver();
String getBrowserName();
}



public class Browser implements AutomationMain{

    public void launchBrowser(){
       //launch code
    }

    public Driver getDriver() {
      //  return driver;
    }

    public String getOther() {
        //other
    }
}

cucumber.api.java.ObjectFactory
