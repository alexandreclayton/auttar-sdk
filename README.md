<h1>How to use:</h1>
<pre>
let _AuttarSDK = new AuttarSDK("ws://192.168.25.41:2500");
await _AuttarSDK.CreditoAVista(2108).then(({data}) => {
            alert(JSON.stringify(data));
        }, (err) => {
            console.log(err);
        });
</pre>
