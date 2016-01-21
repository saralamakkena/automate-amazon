# automate-amazon
<i>December 2015 - January 2016</i><br>
<p>A practice automation test framework for Amazon.com, based on the knowledge gained as a first year automation engieer at Fitbit.com.</p>
<p><b>Problems:</b> I wasn't able to set up tests to run in parallel. I didn't initially build that into DriverUtils, and haven't been able to figure this part out.</p>
<b>Blog: Adventures in Automation</b>
<i>A sample project in order to practice designing automated tests.&nbsp;</i><br />
<blockquote class="tr_bq">
Automate Amazon:<br />
<ul>
<li><a href="http://adventuresinautomation.blogspot.com/2015/12/next-week-automating-amazon-how-i-am.html" target="_blank">Introduction</a></li>
<li>Part One:&nbsp;<a href="http://adventuresinautomation.blogspot.com/2015/12/automate-amazon-development-environment.html" target="_blank">Development Environment Setup</a></li>
<li>Part Two:&nbsp;<a href="http://adventuresinautomation.blogspot.com/2015/12/automate-amazon-sketch-out-use-case.html" target="_blank">Sketch Out a Use Case</a></li>
<li>Part Three:&nbsp;<a href="http://adventuresinautomation.blogspot.com/2015/12/automate-amazon-commonutils-methods-and.html" target="_blank">CommonUtils, methods and exceptions</a></li>
<li>Part Four:&nbsp;<a href="http://adventuresinautomation.blogspot.com/2015/12/automate-amazon-writing-sign-in-test.html" target="_blank">Writing a Sign In Test</a></li>
<li>Part Five:&nbsp;<a href="http://adventuresinautomation.blogspot.com/2016/01/automate-amazon-productenums-and.html" target="_blank">Product Enums and Product Objects</a></li>
<li>Part Six:&nbsp;<a href="http://adventuresinautomation.blogspot.com/2016/01/automate-amazon-initializing-login-and.html" target="_blank">Initializing Login and Cart</a></li>
<li>Part Seven:&nbsp;<a href="http://adventuresinautomation.blogspot.com/2016/01/automate-amazon-writing-shopping-cart.html" target="_blank">Writing a Shopping Cart Test</a></li>
<li>Part Eight:&nbsp;<a href="http://adventuresinautomation.blogspot.com/2016/01/automate-amazon-sketch-of-possible-data.html" target="_blank">Data Driven Tests with TestNG XML</a></li>
</ul>
</blockquote>

The directory structure:
<br />
<b>src/test/java</b><br />
<ul>
<li>actions</li>
<ul>
<li>OrderActions</li>
</ul>
<li>base</li>
<ul>
<li>LoadProperties</li>
</ul>
<li>enums</li>
<ul>
<li>Products</li>
<li>Url</li>
</ul>
<li>pages</li>
<ul>
<li>HomePage</li>
<li>SignInPage</li>
<li>ProductPage</li>
<li>ShoppingCartPage</li>
<li>ShoppingCartReviewPage</li>
</ul>
<li>pojo</li>
<ul>
<li>Book</li>
</ul>
<li>properties</li>
<ul>
<li>user.properties</li>
</ul>
<li>testcases</li>
<ul>
<li>PurchaseOrderTest</li>
</ul>
<li>utils</li>
<ul>
<li>CommonUtils</li>
<li>DriverUtils</li>
</ul>
</ul>
