<h1>MongoDB Compass Snap</h1>
<p>MongoDB compass packaged as a snap. This should run in any Linux environments that support snaps which includes all versions of Ubuntu 16.04 and higher, as well as other distros (manual installation of snapd may be required).</p>

<h2>Setup</h2>
<span>Create snap build environment on Ubuntu 18.04</span><br>
<code>sudo snap install snapcraft</code><br>
<span>From the 'mongodb-compass-snap' directory, run:</span><br>
<code>snapcraft</code><br>
<code>sudo snap install ./compass-snap_0.1_amd64.snap</code>

<p>When you run the snapcraft command, it'll probably walk you through setting up multipass, just stick with all the defaults.</p>

<a href="https://snapcraft.io/">Snapcraft documentation</a>