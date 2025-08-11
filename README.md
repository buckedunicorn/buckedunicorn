<div align="center">

<img src="assets/logo.webp" alt="BuckedUnicorn" width="120" style="margin-bottom: 20px;" />

<h1 style="margin: 0; font-size: 3em; font-weight: 800; background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text;">
BuckedUnicorn
</h1>

<p style="font-size: 1.2em; color: #666; margin: 10px 0 20px 0;">
<strong>Backend Infrastructure Engineer</strong><br/>
<em>Building systems that scale, securing by design, optimizing for reliability</em>
</p>

<div style="display: flex; justify-content: center; gap: 15px; margin: 20px 0;">
  <div style="text-align: center; padding: 10px; background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); border-radius: 10px; color: white; min-width: 80px;">
    <div style="font-size: 1.5em; font-weight: bold;">5+</div>
    <div style="font-size: 0.8em;">Years</div>
  </div>
  <div style="text-align: center; padding: 10px; background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%); border-radius: 10px; color: white; min-width: 80px;">
    <div style="font-size: 1.5em; font-weight: bold;">99.9%</div>
    <div style="font-size: 0.8em;">Uptime</div>
  </div>
  <div style="text-align: center; padding: 10px; background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%); border-radius: 10px; color: white; min-width: 80px;">
    <div style="font-size: 1.5em; font-weight: bold;">50M+</div>
    <div style="font-size: 0.8em;">Requests/Day</div>
  </div>
</div>

<a href="https://github.com/buckedunicorn">
  <img alt="Follow @buckedunicorn" src="https://img.shields.io/github/followers/buckedunicorn?label=Follow&style=for-the-badge&color=667eea&labelColor=2d3748" />
</a>

</div>

<br/>

<div align="center">
  <svg width="600" height="80" viewBox="0 0 600 80" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <linearGradient id="textGrad" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" style="stop-color:#667eea;stop-opacity:1" />
        <stop offset="50%" style="stop-color:#764ba2;stop-opacity:1" />
        <stop offset="100%" style="stop-color:#f093fb;stop-opacity:1" />
      </linearGradient>
    </defs>
    <text x="50%" y="50%" dominant-baseline="middle" text-anchor="middle" fill="url(#textGrad)" 
          font-family="ui-monospace, 'Cascadia Code', 'Source Code Pro', Menlo, Monaco, Consolas, monospace" 
          font-size="16" font-weight="600">
      $ ./deploy --zero-downtime --secure-by-default --performance-first
    </text>
  </svg>
</div>

---

<table width="100%" style="border-collapse: collapse; margin: 30px 0;">
<tr>
<td width="33%" style="vertical-align: top; padding: 20px; border-right: 2px solid #e2e8f0;">
<h3 style="margin: 0 0 15px 0; color: #667eea;">🏗️ Infrastructure</h3>
<p style="margin: 0; color: #4a5568; line-height: 1.6;">
Design distributed systems that gracefully handle failure modes, scale horizontally, and maintain strong consistency guarantees where needed.
</p>
</td>
<td width="33%" style="vertical-align: top; padding: 20px; border-right: 2px solid #e2e8f0;">
<h3 style="margin: 0 0 15px 0; color: #764ba2;">🔐 Security</h3>
<p style="margin: 0; color: #4a5568; line-height: 1.6;">
Implement zero-trust architectures with defense-in-depth strategies, automated compliance, and incident response playbooks.
</p>
</td>
<td width="33%" style="vertical-align: top; padding: 20px;">
<h3 style="margin: 0 0 15px 0; color: #f093fb;">⚡ Performance</h3>
<p style="margin: 0; color: #4a5568; line-height: 1.6;">
Optimize critical paths with profiling, caching strategies, and resource management to achieve sub-100ms response times.
</p>
</td>
</tr>
</table>

## 🎯 Engineering Philosophy

<blockquote style="border-left: 4px solid #667eea; padding: 20px; background: linear-gradient(135deg, #f8faff 0%, #f0f4ff 100%); margin: 20px 0; border-radius: 0 8px 8px 0;">
<p style="margin: 0; font-style: italic; color: #4a5568; font-size: 1.1em; line-height: 1.6;">
"Systems that can't be operated shouldn't be built. Security that isn't automated won't happen. Performance that isn't measured doesn't exist."
</p>
</blockquote>

<details>
<summary><b>🔧 Backend Patterns I Live By</b></summary>
<br/>

<table style="width: 100%; border-collapse: collapse;">
<thead>
<tr style="background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); color: white;">
<th style="padding: 12px; text-align: left; font-weight: 600;">Pattern</th>
<th style="padding: 12px; text-align: left; font-weight: 600;">Problem it Solves</th>
<th style="padding: 12px; text-align: left; font-weight: 600;">Impact</th>
</tr>
</thead>
<tbody>
<tr style="background: #f8faff;">
<td style="padding: 12px; font-family: monospace; color: #667eea; font-weight: 600;">Transactional Outbox</td>
<td style="padding: 12px; color: #4a5568;">Distributed transactions across services</td>
<td style="padding: 12px; color: #22543d;">Guaranteed event delivery</td>
</tr>
<tr>
<td style="padding: 12px; font-family: monospace; color: #667eea; font-weight: 600;">Circuit Breaker + Timeout</td>
<td style="padding: 12px; color: #4a5568;">Cascading failures from flaky dependencies</td>
<td style="padding: 12px; color: #22543d;">Fast failure, system stability</td>
</tr>
<tr style="background: #f8faff;">
<td style="padding: 12px; font-family: monospace; color: #667eea; font-weight: 600;">Idempotency Keys</td>
<td style="padding: 12px; color: #4a5568;">Duplicate requests, retry safety</td>
<td style="padding: 12px; color: #22543d;">Zero data corruption</td>
</tr>
<tr>
<td style="padding: 12px; font-family: monospace; color: #667eea; font-weight: 600;">CQRS (Selective)</td>
<td style="padding: 12px; color: #4a5568;">Read/write performance mismatches</td>
<td style="padding: 12px; color: #22543d;">10x read optimization</td>
</tr>
<tr style="background: #f8faff;">
<td style="padding: 12px; font-family: monospace; color: #667eea; font-weight: 600;">Saga Pattern</td>
<td style="padding: 12px; color: #4a5568;">Long-running business processes</td>
<td style="padding: 12px; color: #22543d;">Reliable compensation</td>
</tr>
</tbody>
</table>

</details>

<details>
<summary><b>🚀 DevOps Practices That Ship</b></summary>
<br/>

<div style="display: grid; grid-template-columns: 1fr 1fr; gap: 20px; margin: 20px 0;">

<div style="padding: 20px; background: linear-gradient(135deg, #e6fffa 0%, #d6f5f5 100%); border-radius: 10px; border-left: 4px solid #4fd1c7;">
<h4 style="margin: 0 0 10px 0; color: #234e52;">🔄 CI/CD Pipeline</h4>
<ul style="margin: 0; padding-left: 20px; color: #4a5568;">
<li>Build → Test → SBOM → Scan → Sign</li>
<li>OIDC to cloud (zero long-lived secrets)</li>
<li>Progressive deployment with rollback</li>
<li>Automated compliance validation</li>
</ul>
</div>

<div style="padding: 20px; background: linear-gradient(135deg, #fef5e7 0%, #fed7aa 100%); border-radius: 10px; border-left: 4px solid #f6ad55;">
<h4 style="margin: 0 0 10px 0; color: #744210;">📊 Observability Stack</h4>
<ul style="margin: 0; padding-left: 20px; color: #4a5568;">
<li>Distributed tracing with correlation IDs</li>
<li>RED + USE metrics dashboards</li>
<li>SLO/SLI with error budgets</li>
<li>Automated alerting with runbooks</li>
</ul>
</div>

<div style="padding: 20px; background: linear-gradient(135deg, #e6f3ff 0%, #bfdbfe 100%); border-radius: 10px; border-left: 4px solid #60a5fa;">
<h4 style="margin: 0 0 10px 0; color: #1e40af;">🏗️ Infrastructure</h4>
<ul style="margin: 0; padding-left: 20px; color: #4a5568;">
<li>Terraform with policy gates</li>
<li>Immutable infrastructure</li>
<li>Auto-scaling with cost optimization</li>
<li>Multi-region disaster recovery</li>
</ul>
</div>

<div style="padding: 20px; background: linear-gradient(135deg, #f0fff4 0%, #c6f6d5 100%); border-radius: 10px; border-left: 4px solid #68d391;">
<h4 style="margin: 0 0 10px 0; color: #22543d;">🔐 Security Automation</h4>
<ul style="margin: 0; padding-left: 20px; color: #4a5568;">
<li>SAST/DAST in every pipeline</li>
<li>Container image vulnerability scanning</li>
<li>Secret rotation and management</li>
<li>Compliance as code (SOC2/GDPR)</li>
</ul>
</div>

</div>

</details>

<details>
<summary><b>💡 Recent Engineering Wins</b></summary>
<br/>

<div style="background: linear-gradient(135deg, #667eea11 0%, #764ba211 100%); padding: 25px; border-radius: 10px; margin: 20px 0;">

<div style="display: grid; grid-template-columns: 1fr 1fr 1fr; gap: 20px; margin-bottom: 20px;">
<div style="text-align: center; padding: 15px; background: white; border-radius: 8px; box-shadow: 0 2px 4px rgba(0,0,0,0.1);">
<div style="font-size: 2em; font-weight: 800; color: #667eea;">40%</div>
<div style="color: #4a5568; font-size: 0.9em;">Cost Reduction</div>
</div>
<div style="text-align: center; padding: 15px; background: white; border-radius: 8px; box-shadow: 0 2px 4px rgba(0,0,0,0.1);">
<div style="font-size: 2em; font-weight: 800; color: #764ba2;">10x</div>
<div style="color: #4a5568; font-size: 0.9em;">Performance Gain</div>
</div>
<div style="text-align: center; padding: 15px; background: white; border-radius: 8px; box-shadow: 0 2px 4px rgba(0,0,0,0.1);">
<div style="font-size: 2em; font-weight: 800; color: #f093fb;">30s</div>
<div style="color: #4a5568; font-size: 0.9em;">Deploy Time</div>
</div>
</div>

<ul style="color: #4a5568; line-height: 1.8;">
<li><strong>Microservices Migration:</strong> Decomposed monolith to 15 services with zero-downtime deployment pipeline</li>
<li><strong>Security Hardening:</strong> Implemented zero-trust architecture with automated policy enforcement</li>
<li><strong>Performance Optimization:</strong> Reduced P99 latency from 2.3s to 180ms through caching and query optimization</li>
<li><strong>Cost Engineering:</strong> Right-sized infrastructure and implemented intelligent auto-scaling, saving $200K annually</li>
</ul>

</div>

</details>

## 🛠️ Technology Arsenal

<div style="margin: 30px 0;">

<table width="100%" style="border-collapse: collapse; border-spacing: 0;">
<tr>
<td width="50%" style="vertical-align: top; padding: 0 10px 0 0;">

<div style="background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); border-radius: 15px; padding: 25px; margin-bottom: 20px; color: white;">
<div style="display: flex; align-items: center; margin-bottom: 15px;">
<div style="font-size: 1.8em; margin-right: 12px;">⚡</div>
<h3 style="margin: 0; font-size: 1.3em; font-weight: 700;">Core Languages</h3>
</div>
<div style="display: grid; grid-template-columns: 1fr 1fr; gap: 10px;">
<div style="background: rgba(255,255,255,0.15); padding: 12px; border-radius: 8px; text-align: center; border: 1px solid rgba(255,255,255,0.2);">
<div style="font-weight: 700; font-size: 1.1em;">Go</div>
<div style="font-size: 0.8em; opacity: 0.9;">Production APIs</div>
</div>
<div style="background: rgba(255,255,255,0.15); padding: 12px; border-radius: 8px; text-align: center; border: 1px solid rgba(255,255,255,0.2);">
<div style="font-weight: 700; font-size: 1.1em;">Rust</div>
<div style="font-size: 0.8em; opacity: 0.9;">Systems & WASM</div>
</div>
<div style="background: rgba(255,255,255,0.15); padding: 12px; border-radius: 8px; text-align: center; border: 1px solid rgba(255,255,255,0.2);">
<div style="font-weight: 700; font-size: 1.1em;">TypeScript</div>
<div style="font-size: 0.8em; opacity: 0.9;">Full-stack web</div>
</div>
<div style="background: rgba(255,255,255,0.15); padding: 12px; border-radius: 8px; text-align: center; border: 1px solid rgba(255,255,255,0.2);">
<div style="font-weight: 700; font-size: 1.1em;">Python</div>
<div style="font-size: 0.8em; opacity: 0.9;">Data & DevOps</div>
</div>
</div>
</div>

<div style="background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%); border-radius: 15px; padding: 25px; color: white;">
<div style="display: flex; align-items: center; margin-bottom: 15px;">
<div style="font-size: 1.8em; margin-right: 12px;">🗄️</div>
<h3 style="margin: 0; font-size: 1.3em; font-weight: 700;">Data & Messaging</h3>
</div>
<div style="display: grid; grid-template-columns: 1fr 1fr; gap: 10px;">
<div style="background: rgba(255,255,255,0.15); padding: 12px; border-radius: 8px; text-align: center; border: 1px solid rgba(255,255,255,0.2);">
<div style="font-weight: 700; font-size: 1.1em;">PostgreSQL</div>
<div style="font-size: 0.8em; opacity: 0.9;">Primary store</div>
</div>
<div style="background: rgba(255,255,255,0.15); padding: 12px; border-radius: 8px; text-align: center; border: 1px solid rgba(255,255,255,0.2);">
<div style="font-weight: 700; font-size: 1.1em;">Redis</div>
<div style="font-size: 0.8em; opacity: 0.9;">Cache & sessions</div>
</div>
<div style="background: rgba(255,255,255,0.15); padding: 12px; border-radius: 8px; text-align: center; border: 1px solid rgba(255,255,255,0.2);">
<div style="font-weight: 700; font-size: 1.1em;">Kafka</div>
<div style="font-size: 0.8em; opacity: 0.9;">Event streaming</div>
</div>
<div style="background: rgba(255,255,255,0.15); padding: 12px; border-radius: 8px; text-align: center; border: 1px solid rgba(255,255,255,0.2);">
<div style="font-weight: 700; font-size: 1.1em;">ClickHouse</div>
<div style="font-size: 0.8em; opacity: 0.9;">Analytics</div>
</div>
</div>
</div>

</td>
<td width="50%" style="vertical-align: top; padding: 0 0 0 10px;">

<div style="background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%); border-radius: 15px; padding: 25px; margin-bottom: 20px; color: white;">
<div style="display: flex; align-items: center; margin-bottom: 15px;">
<div style="font-size: 1.8em; margin-right: 12px;">☁️</div>
<h3 style="margin: 0; font-size: 1.3em; font-weight: 700;">Cloud & Infrastructure</h3>
</div>
<div style="display: grid; grid-template-columns: 1fr 1fr; gap: 10px;">
<div style="background: rgba(255,255,255,0.15); padding: 12px; border-radius: 8px; text-align: center; border: 1px solid rgba(255,255,255,0.2);">
<div style="font-weight: 700; font-size: 1.1em;">AWS</div>
<div style="font-size: 0.8em; opacity: 0.9;">Multi-region</div>
</div>
<div style="background: rgba(255,255,255,0.15); padding: 12px; border-radius: 8px; text-align: center; border: 1px solid rgba(255,255,255,0.2);">
<div style="font-weight: 700; font-size: 1.1em;">Kubernetes</div>
<div style="font-size: 0.8em; opacity: 0.9;">Orchestration</div>
</div>
<div style="background: rgba(255,255,255,0.15); padding: 12px; border-radius: 8px; text-align: center; border: 1px solid rgba(255,255,255,0.2);">
<div style="font-weight: 700; font-size: 1.1em;">Terraform</div>
<div style="font-size: 0.8em; opacity: 0.9;">IaC & policy</div>
</div>
<div style="background: rgba(255,255,255,0.15); padding: 12px; border-radius: 8px; text-align: center; border: 1px solid rgba(255,255,255,0.2);">
<div style="font-weight: 700; font-size: 1.1em;">Docker</div>
<div style="font-size: 0.8em; opacity: 0.9;">Containerization</div>
</div>
</div>
</div>

<div style="background: linear-gradient(135deg, #43e97b 0%, #38f9d7 100%); border-radius: 15px; padding: 25px; color: white;">
<div style="display: flex; align-items: center; margin-bottom: 15px;">
<div style="font-size: 1.8em; margin-right: 12px;">🔐</div>
<h3 style="margin: 0; font-size: 1.3em; font-weight: 700;">Security & Observability</h3>
</div>
<div style="display: grid; grid-template-columns: 1fr 1fr; gap: 10px;">
<div style="background: rgba(255,255,255,0.15); padding: 12px; border-radius: 8px; text-align: center; border: 1px solid rgba(255,255,255,0.2);">
<div style="font-weight: 700; font-size: 1.1em;">Vault</div>
<div style="font-size: 0.8em; opacity: 0.9;">Secret mgmt</div>
</div>
<div style="background: rgba(255,255,255,0.15); padding: 12px; border-radius: 8px; text-align: center; border: 1px solid rgba(255,255,255,0.2);">
<div style="font-weight: 700; font-size: 1.1em;">Prometheus</div>
<div style="font-size: 0.8em; opacity: 0.9;">Metrics</div>
</div>
<div style="background: rgba(255,255,255,0.15); padding: 12px; border-radius: 8px; text-align: center; border: 1px solid rgba(255,255,255,0.2);">
<div style="font-weight: 700; font-size: 1.1em;">Grafana</div>
<div style="font-size: 0.8em; opacity: 0.9;">Dashboards</div>
</div>
<div style="background: rgba(255,255,255,0.15); padding: 12px; border-radius: 8px; text-align: center; border: 1px solid rgba(255,255,255,0.2);">
<div style="font-weight: 700; font-size: 1.1em;">Jaeger</div>
<div style="font-size: 0.8em; opacity: 0.9;">Tracing</div>
</div>
</div>
</div>

</td>
</tr>
</table>

<div align="center" style="margin: 25px 0;">
<div style="background: linear-gradient(135deg, #667eea 0%, #764ba2 50%, #f093fb 100%); padding: 3px; border-radius: 25px; display: inline-block;">
<div style="background: white; padding: 12px 25px; border-radius: 22px; display: inline-block;">
<span style="font-family: ui-monospace, 'Cascadia Code', monospace; background: linear-gradient(135deg, #667eea 0%, #764ba2 50%, #f093fb 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent; font-weight: 700;">
Stack chosen for production reliability, not resume padding
</span>
</div>
</div>
</div>

</div>

---

## 🎖️ Current Focus & Exploration

<table width="100%" style="margin: 20px 0;">
<tr>
<td width="50%" style="vertical-align: top; padding: 20px;">
<h4 style="margin: 0 0 15px 0; color: #667eea;">🔥 Production Work</h4>
<ul style="color: #4a5568; line-height: 1.7;">
<li>Building event-driven microservices with Go + NATS</li>
<li>Implementing policy-as-code security with OPA/Rego</li>
<li>Optimizing Postgres for high-throughput analytical queries</li>
<li>Designing multi-region disaster recovery architectures</li>
</ul>
</td>
<td width="50%" style="vertical-align: top; padding: 20px;">
<h4 style="margin: 0 0 15px 0; color: #f093fb;">🧪 Learning & Experiments</h4>
<ul style="color: #4a5568; line-height: 1.7;">
<li>Rust for embedded systems and WebAssembly</li>
<li>eBPF for observability and security monitoring</li>
<li>Istio service mesh for zero-trust networking</li>
<li>WASM-based serverless runtime architectures</li>
</ul>
</td>
</tr>
</table>

## 📈 GitHub Activity

<div align="center">
<img src="https://github-readme-stats.vercel.app/api?username=buckedunicorn&show_icons=true&theme=radical&hide_border=true&bg_color=0d1117&title_color=667eea&icon_color=f093fb&text_color=c9d1d9&custom_title=BuckedUnicorn%27s%20GitHub%20Stats" height="200"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=buckedunicorn&theme=radical&hide_border=true&background=0d1117&stroke=667eea&ring=f093fb&fire=667eea&currStreakLabel=f093fb" height="200"/>
</div>

<div align="center" style="margin: 20px 0;">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=buckedunicorn&bg_color=0d1117&color=667eea&line=f093fb&point=c9d1d9&area=true&hide_border=true" width="90%"/>
</div>

## 🤝 Let's Connect

<div align="center" style="margin: 30px 0;">

<table style="border-collapse: collapse; margin: 0 auto;">
<tr>
<td style="padding: 15px; text-align: center;">
<a href="https://github.com/buckedunicorn" style="text-decoration: none;">
<div style="width: 60px; height: 60px; background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); border-radius: 15px; display: flex; align-items: center; justify-content: center; margin: 0 auto 8px auto;">
<svg width="30" height="30" fill="white" viewBox="0 0 24 24">
<path d="M12 0C5.374 0 0 5.373 0 12c0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23A11.509 11.509 0 0112 5.803c1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576C20.566 21.797 24 17.3 24 12c0-6.627-5.373-12-12-12z"/>
</svg>
</div>
<div style="color: #4a5568; font-weight: 600; font-size: 0.9em;">GitHub</div>
</a>
</td>
<td style="padding: 15px; text-align: center;">
<a href="https://linkedin.com/in/buckedunicorn" style="text-decoration: none;">
<div style="width: 60px; height: 60px; background: linear-gradient(135deg, #0077b5 0%, #005885 100%); border-radius: 15px; display: flex; align-items: center; justify-content: center; margin: 0 auto 8px auto;">
<svg width="30" height="30" fill="white" viewBox="0 0 24 24">
<path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433c-1.144 0-2.063-.926-2.063-2.065 0-1.138.92-2.063 2.063-2.063 1.14 0 2.064.925 2.064 2.063 0 1.139-.925 2.065-2.064 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/>
</svg>
</div>
<div style="color: #4a5568; font-weight: 600; font-size: 0.9em;">LinkedIn</div>
</a>
</td>
<td style="padding: 15px; text-align: center;">
<a href="https://twitter.com/buckedunicorn" style="text-decoration: none;">
<div style="width: 60px; height: 60px; background: linear-gradient(135deg, #1da1f2 0%, #0d8bd9 100%); border-radius: 15px; display: flex; align-items: center; justify-content: center; margin: 0 auto 8px auto;">
<svg width="30" height="30" fill="white" viewBox="0 0 24 24">
<path d="M23.953 4.57a10 10 0 01-2.825.775 4.958 4.958 0 002.163-2.723c-.951.555-2.005.959-3.127 1.184a4.92 4.92 0 00-8.384 4.482C7.69 8.095 4.067 6.13 1.64 3.162a4.822 4.822 0 00-.666 2.475c0 1.71.87 3.213 2.188 4.096a4.904 4.904 0 01-2.228-.616v.06a4.923 4.923 0 003.946 4.827 4.996 4.996 0 01-2.212.085 4.936 4.936 0 004.604 3.417 9.867 9.867 0 01-6.102 2.105c-.39 0-.779-.023-1.17-.067a13.995 13.995 0 007.557 2.209c9.053 0 13.998-7.496 13.998-13.985 0-.21 0-.42-.015-.63A9.935 9.935 0 0024 4.59z"/>
</svg>
</div>
<div style="color: #4a5568; font-weight: 600; font-size: 0.9em;">Twitter</div>
</a>
</td>
<td style="padding: 15px; text-align: center;">
<a href="https://medium.com/@buckedunicorn" style="text-decoration: none;">
<div style="width: 60px; height: 60px; background: linear-gradient(135deg, #00ab6c 0%, #00d084 100%); border-radius: 15px; display: flex; align-items: center; justify-content: center; margin: 0 auto 8px auto;">
<svg width="30" height="30" fill="white" viewBox="0 0 24 24">
<path d="M13.54 12a6.8 6.8 0 01-6.77 6.82A6.8 6.8 0 010 12a6.8 6.8 0 016.77-6.82A6.8 6.8 0 0113.54 12zM20.96 12c0 3.54-1.51 6.42-3.38 6.42-1.87 0-3.39-2.88-3.39-6.42s1.52-6.42 3.39-6.42 3.38 2.88 3.38 6.42M24 12c0 3.17-.53 5.75-1.19 5.75-.66 0-1.19-2.58-1.19-5.75s.53-5.75 1.19-5.75C23.47 6.25 24 8.83 24 12z"/>
</svg>
</div>
<div style="color: #4a5568; font-weight: 600; font-size: 0.9em;">Medium</div>
</a>
</td>
<td style="padding: 15px; text-align: center;">
<a href="https://stackoverflow.com/users/31219209/bucked-unicorn" style="text-decoration: none;">
<div style="width: 60px; height: 60px; background: linear-gradient(135deg, #f48024 0%, #d86613 100%); border-radius: 15px; display: flex; align-items: center; justify-content: center; margin: 0 auto 8px auto;">
<svg width="30" height="30" fill="white" viewBox="0 0 24 24">
<path d="M15.725 0l-1.72 1.277 6.39 8.588 1.716-1.277L15.725 0zm-3.94 3.418l-1.369 1.644 8.225 6.85 1.369-1.644-8.225-6.85zm-3.15 4.465l-.905 1.94 9.702 4.517.904-1.94-9.701-4.517zm-1.85 4.86l-.44 2.093 10.473 2.201.44-2.092L6.785 12.743zM24 22.25h-2.25V24H24v-1.75zM2.25 22.25H0V24h2.25v-1.75zm19.5-2.25H2.25v2.25h19.5v-2.25zM6.59 17.77l10.57.001.001 2.202-10.566-.001L6.59 17.77z"/>
</svg>
</div>
<div style="color: #4a5568; font-weight: 600; font-size: 0.9em;">Stack Overflow</div>
</a>
</td>
</tr>
</table>

</div>

<div align="center" style="margin: 30px 0;">
<div style="background: linear-gradient(135deg, #667eea 0%, #764ba2 50%, #f093fb 100%); padding: 2px; border-radius: 50px; display: inline-block;">
<div style="background: white; padding: 15px 30px; border-radius: 48px; display: inline-block;">
<span style="font-family: ui-monospace, 'Cascadia Code', 'Source Code Pro', Menlo, Monaco, Consolas, monospace; background: linear-gradient(135deg, #667eea 0%, #764ba2 50%, #f093fb 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text; font-weight: 700; font-size: 1.1em;">
Always building, always learning, always shipping. 🚀
</span>
</div>
</div>
</div>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12&height=100&section=footer" width="100%" />
</div>
