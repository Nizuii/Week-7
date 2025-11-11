# What is DOS
<ul>
  <li>DOS stands for denial of service.</li>
  <li>In simple words it means crashing or overloading a server or website so users cant access it.</li>
  <li>So a single computer flooding a target with traffic or request until it stops responding is called DOS attack.</li>
</ul>

# What is DDOS
<ul>
  <li>DDOS stands for distributed denial of service.</li>
  <li>The goal is same as DOS but instead its done by using many computer at once.</li>
  <li>DDOS - Distrubuted means it comes from many sources, often other infected computers called botnets.</li>
</ul>

<h2>Major impact of DOS/DDOS Attack</h2>
<ol>
  <li>
    <h3>Loss of availability</h3>
    The website, service, or application becomes slow or completely unreachable. When people can’t connect, the service is effectively “down” — customers can’t buy, log in, or use features.
  </li>
  <li>
    <h3>Financial damage</h3>
    <ul>
      <li>Immediate lost revenue (e-commerce checkout fails, transactions drop).</li>
      <li>Mitigation costs: paying for DDoS protection, extra bandwidth, emergency engineering time.</li>
      <li>Penalties or SLA payouts if you promised uptime.</li>
    </ul>
  </li>
  <li>
    <h3>Reputation and trust damage</h3>
    Customers and partners notice outages. Repeated incidents erode trust, cause churn, and damage brand image — sometimes permanently.
  </li>
  <li>
    <h3>Operational disruption</h3>
    Internal teams get pulled into firefighting: support queues blow up, engineers stop planned work, timelines slip. Productivity grinds to a halt.
  </li>
  <li>
    <h3>Collateral damage to other systems</h3>
    A big attack can saturate network links or shared infrastructure, causing unrelated services or tenants to suffer too.
  </li>
</ol>

<h3>Mitigations</h3>
<ol>
  <li>Put your site behind a CDN</li>
  <li>Turn on “Under Attack” / challenge mode in the CDN dashboard</li>
  <li>Enable the Web Application Firewall</li>
  <li>Set a basic rate limit (slow down repeat callers)</li>
  <li>Block a country or region temporarily (if attack is concentrated)</li>
  <li>Contact your host or ISP immediately</li>
  <li>Switch to a static maintenance page (save resources)</li>
  <li>Blackholing / sinkholing: throw traffic to a “null” route when it's obviously malicious — quick but can block legitimate users if used bluntly.</li>
  <li>SYN cookies and TCP tuning: protect against connection-table exhaustion (network-level tuning to refuse incomplete handshakes instead of storing them).</li>
  <li>Behavioral filtering (WAF or bot manager): detect patterns that look like bots (no JavaScript, wrong headers) and challenge them (CAPTCHA, JS challenge).</li>
  <li>Upstream filtering with your ISP: the ISP can filter traffic before it reaches your network — essential for large attacks.</li>
</ol>
