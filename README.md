<h2 align="center">📧 Autonomous AI Email Triage & Support Dispatch</h2>

<table width="100%" style="border-collapse: collapse; border: none;">
<tr>
<td width="35%" align="center" valign="top" style="border: none; padding-right: 15px;">

<!-- Dynamic Visual Architecture Flow Diagram generated via QuickChart -->
<img src="https://quickchart.io/graphviz?graph=digraph%20%7B%0A%20%20rankdir%3DTB%3B%0A%20%20bgcolor%3D%22transparent%22%3B%0A%20%20node%20%5Bstyle%3D%22filled%2Crounded%22%2C%20fontcolor%3D%22white%22%2C%20fontname%3D%22sans-serif%22%2C%20shape%3D%22box%22%2C%20margin%3D%220.2%2C0.2%22%2C%20width%3D3%2C%20penwidth%3D0%5D%3B%0A%20%20edge%20%5Bcolor%3D%22%23888888%22%2C%20penwidth%3D2%5D%3B%0A%0A%20%20Email%20%5Blabel%3D%22%F0%9F%93%A7%20Incoming%20Support%20Email%22%2C%20fillcolor%3D%22%23333333%22%5D%3B%0A%20%20Groq%20%5Blabel%3D%22%F0%9F%A7%A0%20Groq%20(Llama-3)%5CnIntent%20%26%20Priority%20Scoring%22%2C%20fillcolor%3D%22%23F55036%22%5D%3B%0A%20%20OpenAI%20%5Blabel%3D%22%E2%9C%A8%20OpenAI%20GPT%5CnAuto-Draft%20Resolution%22%2C%20fillcolor%3D%22%23412991%22%5D%3B%0A%20%20Slack%20%5Blabel%3D%22%F0%9F%92%AC%20Slack%20%26%20Queue%5CnHuman-in-Loop%20Dispatch%22%2C%20fillcolor%3D%22%230E75B6%22%5D%3B%0A%0A%20%20Email%20-%3E%20Groq%20-%3E%20OpenAI%20-%3E%20Slack%3B%0A%7D" width="100%" alt="Visual Flow Diagram of Email Triage Pipeline" />

<br>
<!-- Dynamic HUD / Typing Metric Indicator -->
<img src="https://readme-typing-svg.herokuapp.com?color=F55036&center=true&vCenter=true&lines=P1-P4+Priority+Scoring;Entity+Extraction;Groq-to-OpenAI+Failover;60%25+Faster+Turnaround&width=250&height=40&size=14">

</td>
<td width="65%" valign="top" style="border: none; padding-left: 15px;">

<blockquote>
<b>🚀 Business Impact:</b> Engineered an asynchronous LLM pipeline that successfully cut enterprise ticket turnaround time by <b>60%</b>.
</blockquote>

<p><b>⚙️ Comprehensive Engineering Mechanics:</b></p>
<ul>
<li><b>Intelligent Routing & Scoring:</b> Deployed Groq API (Llama-3) for sub-second intent classification, precise entity extraction, and dynamic P1–P4 priority scoring.</li>
<li><b>Automated Queue Dispatch:</b> Triggered via FastAPI webhooks, featuring intelligent queue routing and automated Slack escalation for high-priority tickets.</li>
<li><b>Context-Aware Draft Generation:</b> Leverages OpenAI GPT models to auto-generate contextually accurate draft replies strictly adhering to JSON-schema outputs.</li>
<li><b>Enterprise Resilience & Safety:</b> Built with a robust Groq-to-OpenAI model failover mechanism, active PII sanitization filters, and a mandatory human-in-the-loop approval gate prior to final dispatch.</li>
</ul>

<p><b>🛠️ Technology Stack:</b></p>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/Groq_API-F55036?style=for-the-badge"/>
<img src="https://img.shields.io/badge/OpenAI_GPT-412991?style=for-the-badge&logo=openai&logoColor=white"/>
<img src="https://img.shields.io/badge/Slack_API-4A154B?style=for-the-badge&logo=slack&logoColor=white"/>

</td>
</tr>
</table>
