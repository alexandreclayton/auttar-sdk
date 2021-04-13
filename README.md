<h1>How to use:</h1>
<pre>
const _AuttarSDK = new AuttarSDK("ws://192.168.25.41:2500");
_AuttarSDK.CreditoAVista(2108).then((resp) => {
   const { data } = resp
   alert(JSON.stringify(data));
 }, (err) => {
   console.log(err);
});
</pre>
