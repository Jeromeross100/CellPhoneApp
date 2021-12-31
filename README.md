# CellPhoneApp
package abstraction;

abstract class CellPhone {
	String appversion;
	
	public void showCalling()
	{
		System.out.println("Phone Calling and Receiving...");
	}
	public void showMsg()
	{
		System.out.println("Sending and Receive MSG.....");
	}
	CellPhone(String appversion)
	{
		this.appversion=appversion;
		System.out.println("Show App Version..: "+appversion);
	}
	abstract void gameApp();
	abstract void showWeatherApp();

}
