<div class="versiontext hero">
<div class="container hero-container">
<h1>Bitcoin version 0.3.21 released</h1>
<p class="summary">27 April 2011</p>
</div>
</div>
<div class="toc-container release-content">
<div class="row toc-row">
<div class="toccontent version-content">
<article class="article">
<p>Binaries for Bitcoin version 0.3.21 are available at:<span>&nbsp;</span><a href="http://sourceforge.net/projects/bitcoin/files/Bitcoin/bitcoin-0.3.21/">http://sourceforge.net/projects/bitcoin/files/Bitcoin/bitcoin-0.3.21/</a></p>
<p>Changes and new features from the 0.3.20 release include:</p>
<ul>
<li>Universal Plug and Play support. Enable automatic opening of a port for incoming connections by running bitcoin or bitcoind with the</li>
<li>-upnp=1 command line switch or using the Options dialog box.</li>
<li>Support for full-precision bitcoin amounts. You can now send, and bitcoin will display, bitcoin amounts smaller than 0.01. However, sending fewer than 0.01 bitcoins still requires a 0.01 bitcoin fee (so you can send 1.0001 bitcoins without a fee, but you will be asked to pay a fee if you try to send 0.0001).</li>
<li>A new method of finding bitcoin nodes to connect with, via DNS A records. Use the -dnsseed option to enable.</li>
</ul>
<p>For developers, changes to bitcoin&rsquo;s remote-procedure-call API:</p>
<ul>
<li>New rpc command &ldquo;sendmany&rdquo; to send bitcoins to more than one address in a single transaction.</li>
<li>Several bug fixes, including a serious intermittent bug that would sometimes cause bitcoind to stop accepting rpc requests.</li>
<li>-logtimestamps option, to add a timestamp to each line in debug.log.</li>
<li>Immature blocks (newly generated, under 120 confirmations) are now shown in listtransactions.</li>
</ul>
</article>
</div>
</div>
</div>
<p><a class="back-link" href="https://bitcoin.org/en/version-history">Go back to the version history</a></p>
