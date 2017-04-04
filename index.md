# Welcome to Demoland!

## Note the Agent.ai Chat Widget in the lower right-hand corner
<!-- agent.ai chat widget begin -->
   <script id="user-care-script" src="https://webclient.agent.ai/js/agentai.js">
   </script>
   
Customer ID: <input type='text' name='cid' id='cid' autofocus>
<button onclick="myFunction()">Login</button>

<script>
function myFunction() {
    var x = document.getElementById('cid').value;
    AgentAI.initialize({
           'app_id': 'udvlVlwJLtdfGpuFvelhqw',
           'api_key': 'AHTN65UUJVE4Q0002UPWNPOZ262FC3DAWLS2KJH3XE',
           'allow_location': true,
           'api_domain': 'agent-demo01.agent.ai',
           'customer_id': x
    });
}
</script>
<!-- agent.ai chat widget end -->
