<h1 align="center">NirmataTestNet</h1>
<p>This repository contains tools for accessing the test network</p>
<h2 align="center">Why is this necessary?</h2>
<h3>For the team</h3>
<p>All updates must be checked and fixed before they are implemented into the main network, since if something goes wrong in the test network, it will not be scary, but if the main network crashes after the update... This is unacceptable.</p>
<h3>For developers</h3>
<p>Software developers do not need to run their own node, they can use ours to develop and test their products without worrying about losing funds, coins in the test network are easy to get for tests and it is not scary to lose them since they cost nothing</p>
<h3>For users</h3>
<p>You can check out the early versions of future updates</p>
<h2 align="center">How to get started</h2>
<p>In the releases attached to this repository, you will find the latest builds for the test network, download the necessary one, depending on your operating system.</p>
<p>You will find everything you need in the release archive.</p>
<p>Nirmata.exe/Nirmata.sh (win/lin), a full node startup file with a graphical interface.</p>
<p>nirmatad, the test network daemon.</p>
<p>simplewallet, CLI wallet.</p>
<h3>How to get coins</h3>
<p>Run Nirmata.exe/Nirmata.sh (win/lin), wait for synchronization, create a wallet and copy the address, close it Nirmata.exe/Nirmata.sh</p>
<p>Run nirmatad, after starting the daemon, enter the command in its window, start_mining "your address" 1, this command will start the mining process using one core of your processor, just wait for the solutions for which you will receive a reward and be able to enable pos in your wallet. </p>
<p>Do not run at the same time Nirmata.exe/Nirmata.sh and nirmatad, they won't work like that.</p>
<h2>Remember, coins in the test network are worthless, they cannot be sold or transferred to the main network.</h2>
<h2>Do not run the test and main network nodes at the same time, conflicts may occur.</h2>
