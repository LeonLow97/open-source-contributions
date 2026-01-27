# Open Source Contributions

<div align="center">
	<table>
		<tr>
			<th>Issue</th>
			<th>Problem Link</th>
			<th>Pull Request Link</th>
			<th>Repo Stars</th>
		</tr>
		<tr>
			<td>Updated semantic conversion usage with go.opentelemetry.io/otel from v1.25.0 to v1.38.0 in `pkg/translator/azure`</td>
			<td>https://github.com/open-telemetry/opentelemetry-collector-contrib/issues/44801</td>
			<td>https://github.com/open-telemetry/opentelemetry-collector-contrib/pull/45630</td>
			<td><img src="https://img.shields.io/github/stars/open-telemetry/opentelemetry-collector-contrib?style=social" alt="stars"/></td>
		</tr>
		<tr>
			<td>k8sattributes processor to set k8s.node.uid even though k8s.node.name is not requested.</td>
			<td>https://github.com/open-telemetry/opentelemetry-collector-contrib/issues/43865</td>
			<td>https://github.com/open-telemetry/opentelemetry-collector-contrib/pull/45643</td>
			<td><img src="https://img.shields.io/github/stars/open-telemetry/opentelemetry-collector-contrib?style=social" alt="stars"/></td>
		</tr>
		<tr>
			<td>k8sattributes processor to only set `k8s.pod.ip` attribute when it is requested in the `extract.metadata` configuration.</td>
			<td>https://github.com/open-telemetry/opentelemetry-collector-contrib/issues/43862</td>
			<td>https://github.com/open-telemetry/opentelemetry-collector-contrib/pull/43910</td>
			<td><img src="https://img.shields.io/github/stars/open-telemetry/opentelemetry-collector-contrib?style=social" alt="stars"/></td>
		</tr>
		<tr>
			<td>Added Tag parameter to Fluentbit syslog input in ClusterInput CRD so Fluent operator can route logs to specific parsers.</td>
			<td>https://github.com/fluent/fluent-operator/issues/1732</td>
			<td>https://github.com/fluent/fluent-operator/pull/1744</td>
			<td><img src="https://img.shields.io/github/stars/fluent/fluent-operator?style=social" alt="stars"/></td>
		</tr>
		<tr>
			<td>Ensured stable container image tags include the leading "v" (e.g., v2.0.0), fixing the missing v prefix in stable image tagging.</td>
			<td>https://github.com/google/osv-scanner/issues/1976</td>
			<td>https://github.com/google/osv-scanner/pull/2001</td>
			<td><img src="https://img.shields.io/github/stars/google/osv-scanner?style=social" alt="stars"/></td>
		</tr>
		<tr>
			<td>Added a stable tag for the latest stable release on ghcr.io (e.g., tagged 1.9.2 as stable) so users can rely on a stable container image in addition to latest.</td>
			<td>https://github.com/google/osv-scanner/issues/1563</td>
			<td>https://github.com/google/osv-scanner/pull/1882</td>
			<td><img src="https://img.shields.io/github/stars/google/osv-scanner?style=social" alt="stars"/></td>
		</tr>
		<tr>
			<td>Removed redundant loop-variable copy assignments, by relying on Go 1.22's fixed loop-variable capture behavior</td>
			<td>https://github.com/ssvlabs/ssv/issues/2134</td>
			<td>https://github.com/ssvlabs/ssv/pull/2198</td>
			<td><img src="https://img.shields.io/github/stars/ssvlabs/ssv?style=social" alt="stars"/></td>
		</tr>
		<tr>
			<td>Support JSON Array Responses when unmarshaling arrays.</td>
			<td>https://github.com/akuity/kargo/issues/3877</td>
			<td>https://github.com/akuity/kargo/pull/4059</td>
			<td><img src="https://img.shields.io/github/stars/akuity/kargo?style=social" alt="stars"/></td>
		</tr>
		<tr>
			<td>Added test for the network module's `loadOrCreateKey` function to verify it successfully loads a valid key</td>
			<td>https://github.com/pactus-project/pactus/issues/1766</td>
			<td>https://github.com/pactus-project/pactus/pull/1783</td>
			<td><img src="https://img.shields.io/github/stars/pactus-project/pactus?style=social" alt="stars"/></td>
		</tr>
		<tr>
			<td>Added .Log() support after .Limit() in the SQL query builder so chains like `users.Select().Where().Limit(10).Log()` work.</td>
			<td>https://github.com/devasherr/Nexom/issues/3</td>
			<td>https://github.com/devasherr/Nexom/pull/4</td>
			<td><img src="https://img.shields.io/github/stars/devasherr/Nexom?style=social" alt="stars"/></td>
		</tr>
	</table>
</div>
