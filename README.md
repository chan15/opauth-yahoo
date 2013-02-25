<h1>Opauth-Yahoo</h1>
=======
<p><a href="https://github.com/uzyn/opauth">Opauth</a> strategy for Yahoo authentication.</p>

<p>Implemented based on <a href="http://developer.yahoo.com/oauth/guide/oauth-auth-flow.html">http://developer.yahoo.com/oauth/guide/oauth-auth-flow.html</a> using OAuth 1.0.</p>

<p>Opauth is a multi-provider authentication framework for PHP.</p>

<h2>Getting started</h2>

<p>Install Yahoo-Yahoo:</p>

<pre><span class="nb">cd </span>path_to_opauth/Strategy
git clone git://github.com/booper/opauth-yahoo.git Yahoo
</pre>


<p>Sign Up Yahoo App and Get a Consumer Key at  <a href="https://developer.apps.yahoo.com/dashboard/createKey.html">https://developer.apps.yahoo.com/dashboard/createKey.html</a></p>

<p>During registration, indicate the kinds of Yahoo! User data (also called Scopes) you want to access.
Later in the OAuth process, Yahoo! will ask your Users if Yahoo! should allow you to access their User data.
For more information about Scopes, see Scopes section <a href="http://developer.yahoo.com/oauth/guide/oauth-scopes.html">http://developer.yahoo.com/oauth/guide/oauth-scopes.html</a></p>.


<p>Configure Opauth-Yahoo strategy.</p></li>
<p>Direct user to <code>http://path_to_opauth/yahoo</code> to authenticate</p></li>



<h2>
<a href="#strategy-configuration" class="anchor" name="strategy-configuration"><span class="mini-icon mini-icon-link"></span></a>Strategy configuration</h2>

<p>Required parameters:</p>
<code>
'Google' => array(
    'key' => 'Consumer Key',
    'secret' => 'Consumer Secret'
)

</code>
<p>Optional parameters:
Optional parameters: <code>appid</code> ( Provide it if you have several apps in Yahoo.com)

<h2>
<a href="#references" class="anchor" name="references"><span class="mini-icon mini-icon-link"></span></a>References</h2>

<ul>

</ul>

<h2>License</h2>

<p>Opauth-Yahoo is MIT Licensed<br>
Copyright &copy; 2013 Valerii Igumentsev (<a href="http:facebook.com/ibooper">http:facebook.com/ibooper</a>)</p>
>>>>>>> readme
