---
title: "Helm 4 Released"
url: "https://helm.sh/blog/helm-4-released"
date: "Mon, 17 Nov 2025 00:00:00 GMT"
author: ""
feed_url: "https://helm.sh/blog/rss.xml"
---
<p>On Wednesday November 12th, during the <a class="" href="https://sched.co/27Nme" rel="noopener noreferrer" target="_blank">Helm 4 presentation at KubeCon + CloudNativeCon</a>, <a class="" href="https://github.com/helm/helm/releases/tag/v4.0.0" rel="noopener noreferrer" target="_blank">Helm v4.0.0</a> was released. This is the first new major version of Helm in 6 years. </p>
<h2 class="anchor anchorTargetStickyNavbar_Vzrq" id="whats-new">What's New<a class="hash-link" href="https://helm.sh/blog/helm-4-released#whats-new" title="Direct link to What's New">​</a></h2>
<p>Helm v3 has served the Kubernetes community well for many years. During that time we saw new ways to use Helm, new applications installed via charts, the rise of <a class="" href="https://artifacthub.io/" rel="noopener noreferrer" target="_blank">Artifact Hub</a>, and numerous tools that build on top of Helm. We also saw where we wanted to add features but the internal architecture of Helm didn't provide a path forward without breaking public APIs in the SDK. Helm 4 makes those changes to enable new features now and into the future.</p>
<p>Some of the new features include:</p>
<ul>
<li class="">Redesigned plugin system that supports Web Assembly based plugins</li>
<li class="">Post-renderers are now plugins</li>
<li class="">Server side apply is now supported</li>
<li class="">Improved resource watching, to support waiting, based on kstatus</li>
<li class="">Local Content-based caching (e.g. for charts)</li>
<li class="">Logging via slog enabling SDK logging to integrate with modern loggers</li>
<li class="">Reproducible/Idempotent builds of chart archives</li>
<li class="">Updated SDK API including support for multiple chart API versions (new experimental v3 chart API version coming soon)</li>
</ul>
<p>You can learn about more of the changes in the <a class="" href="https://helm.sh/docs/overview">Helm 4 Overview</a>.</p>
<h2 class="anchor anchorTargetStickyNavbar_Vzrq" id="helm-v3-support">Helm v3 Support<a class="hash-link" href="https://helm.sh/blog/helm-4-released#helm-v3-support" title="Direct link to Helm v3 Support">​</a></h2>
<p>When a major version of software comes out, it takes awhile to make the transition. Helm v3 will continue to be supported to enable a clean transition period. The dates of continued support are:</p>
<ul>
<li class="">Bug fixes until July 8th 2026.</li>
<li class="">Security fixes until November 11th 2026.</li>
</ul>
<p>Helm releases updates on Wednesdays (typically the 2nd Wednesday in a month) and these dates correspond with release schedule dates. During this time there will be <strong><em>NO</em></strong> features backported other than updates to the Kubernetes client libraries that enable support of new Kubernetes versions.</p>
<h2 class="anchor anchorTargetStickyNavbar_Vzrq" id="learn-more">Learn More<a class="hash-link" href="https://helm.sh/blog/helm-4-released#learn-more" title="Direct link to Learn More">​</a></h2>
<p>You can learn about the Helm changes in the <a class="" href="https://helm.sh/docs/overview">overview</a> or find all the changes in the <a class="" href="https://helm.sh/docs/changelog">full changelog</a>. The documentation shares many more details as you can find all the ways Helm has stayed the same and the new features you can take advantage of.</p>
