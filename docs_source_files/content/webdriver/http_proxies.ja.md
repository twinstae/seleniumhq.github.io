---
title: "Httpプロキシ"
weight: 7
---

プロキシサーバーは、クライアントとサーバー間の要求の仲介役として機能します。
簡単に言えば、トラフィックはプロキシサーバーを経由して、要求したアドレスに戻り、戻ってきます。

Seleniumを使用した自動化スクリプト用のプロキシサーバーは、

* ネットワークトラフィックをキャプチャする
* ウェブサイトによって行われた模擬バックエンドを呼び出す
* 複雑なネットワークトポロジーまたは厳格な企業の制限/ポリシーの下で、必要なWebサイトにアクセスします。

企業環境でブラウザがURLへの接続に失敗した場合、環境にアクセスするにはプロキシが必要であることが原因であることが最も可能性が高いです。

Selenium WebDriverは設定をプロキシする方法を提供します。


{{< code-tab >}}
  {{< code-panel language="java" >}}
import org.openqa.selenium.Proxy;
import org.openqa.selenium.WebDriver;
import org.openqa.selenium.chrome.ChromeDriver;
import org.openqa.selenium.chrome.ChromeOptions;

public class proxyTest {
  public static void main(String[] args) {
    Proxy proxy = new Proxy();
    proxy.setHttpProxy("<HOST:PORT>");
    ChromeOptions options = new ChromeOptions();
    options.setCapability("proxy", proxy);
    WebDriver driver = new ChromeDriver(options);
    driver.get("https://www.google.com/");
    driver.manage().window().maximize();
    driver.quit();
  }
}
  {{< / code-panel >}}
  {{< code-panel language="python" >}}
# Need PR
  {{< / code-panel >}}
  {{< code-panel language="csharp" >}}
// Need pr
  {{< / code-panel >}}
  {{< code-panel language="ruby" >}}
 # Need PR
  {{< / code-panel >}}
  {{< code-panel language="javascript" >}}
// need PR
  {{< / code-panel >}}
  {{< code-panel language="kotlin" >}}
import org.openqa.selenium.Proxy
import org.openqa.selenium.WebDriver
import org.openqa.selenium.chrome.ChromeDriver
import org.openqa.selenium.chrome.ChromeOptions

class proxyTest {
    fun main() {

        System.setProperty("webdriver.gecko.driver", "/path/to/geckodriver")
        val proxy = Proxy()
        proxy.setHttpProxy("<HOST:PORT>")
        val options = ChromeOptions()
        options.setCapability("proxy", proxy)
        val driver: WebDriver = ChromeDriver(options)
        driver["https://www.google.com/"]
        driver.manage().window().maximize()
        driver.quit()
    }
}
  {{< / code-panel >}}
{{< / code-tab >}}
