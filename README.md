easy way to connect to browser sync without copy and paste the socket.io snippet.

regularly i use gulp and gulp connect to run a testserver on port 9000 on my machine and do:

<pre>
if (window.location.port !== '80' && window.location.port !== '') {
        browserSyncConnect();
}
</pre>

so the live version will not be browser-synced.
