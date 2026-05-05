---
title: "Helm 2to3 is Now Unsupported"
url: "https://helm.sh/blog/helm2to3-becomes-unsupported"
date: "Tue, 16 Jul 2024 00:00:00 GMT"
author: ""
feed_url: "https://helm.sh/blog/rss.xml"
---
<p>Over four years ago, we <a class="" href="https://helm.sh/blog/helm-3-released/" rel="noopener noreferrer" target="_blank">introduced Helm 3</a>, a major evolution in Helm's development. And we <a class="" href="https://helm.sh/blog/2019-10-22-helm-2150-released/" rel="noopener noreferrer" target="_blank">announced</a> at that time that Helm 2 would receive patches and security updates for a year. We also provided a <a class="" href="https://helm.sh/docs/topics/v2_v3_migration/" rel="noopener noreferrer" target="_blank">migration path to Helm 3 from Helm 2</a> and a tool <a class="" href="https://github.com/helm/helm-2to3" rel="noopener noreferrer" target="_blank">helm-2to3</a> to automate migration.</p>
<p>One year later, <a class="" href="https://helm.sh/blog/helm-2-becomes-unsupported/" rel="noopener noreferrer" target="_blank">Helm 2 became unsupported</a>.</p>
<p>Here we are, over 3 years since Helm 2 became unsupported. It would be expected that all users should be migrated to Helm 3 by this time. Following consensus among the Helm org maintainers, we are announcing today the official end of support for the <a class="" href="https://github.com/helm/helm-2to3" rel="noopener noreferrer" target="_blank">helm-2to3</a> tool.</p>
<p>In practice, this means that <strong>Helm 2to3</strong> will receive no more updates (not even security patches).</p>
<p>We strongly discourage the use of the <a class="" href="https://github.com/helm/helm-2to3" rel="noopener noreferrer" target="_blank">helm-2to3</a> tool moving forward, as it will be receiving no future security updates or patches. We hope that it has been a useful tool to aid in the migration from Helm 2 to 3.</p>
