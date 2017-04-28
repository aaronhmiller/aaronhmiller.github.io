# Welcome to Demoland!

## Login and note the Agent.ai Chat Widget in the lower right-hand corner
Customer ID: <input type='text' name='cid' id='cid' autofocus>
<button onclick="myFunction()">Login</button>

## We can show() or hide() it
<input type='button' id='hideshow' value='hide/show' onclick="toggle()">

## View the documentation here
[https://doc.agent.ai/developer/web/](https://doc.agent.ai/developer/web/)

<!-- agent.ai chat widget begin -->
<script id="user-care-script" type="text/javascript" src="https://webclient.agent.ai/js/agentai.js">
</script>
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
AgentAI.tags('index_page');
</script>
<!-- agent.ai chat widget end -->

<script>
function toggle() {
   AgentAI.toggle();
}
</script>
