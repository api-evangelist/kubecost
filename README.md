# Kubecost (kubecost)

Kubecost provides real-time cost monitoring and management for Kubernetes environments. Its APIs enable programmatic access to cost allocation data, asset costs, cloud provider spend, budget governance, cost forecasting, and savings recommendations for optimizing Kubernetes and cloud infrastructure spending.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-search/kubecost/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Cloud Cost, Cost Monitoring, Kubernetes, Optimization, Spending

## Timestamps

- **Created:** 2024-11-13
- **Modified:** 2026-03-16

## APIs

### Kubecost Allocation API

The Allocation API retrieves cost allocation information for any Kubernetes concept, such as cost by namespace, label, deployment, service, and more. It is directly integrated with the Kubecost ETL caching layer and CSV pipeline so it can scale for large clusters.

**Human URL:** [https://docs.kubecost.com/apis/monitoring-apis/api-allocation](https://docs.kubecost.com/apis/monitoring-apis/api-allocation)

#### Tags

- Cost Allocation, Kubernetes, Monitoring

#### Properties

- [Documentation](https://docs.kubecost.com/apis/monitoring-apis/api-allocation)
- [OpenAPI](openapi/kubecost-allocation-openapi.yml)
- [JSONSchema](json-schema/allocation.json)
- [JSONLD](json-ld/kubecost-context.jsonld)

### Kubecost Assets API

The Assets API retrieves backing cost data broken down by individual Kubernetes assets in your cluster, such as nodes, disks, load balancers, and more. It also provides various aggregations of this data.

**Human URL:** [https://docs.kubecost.com/apis/monitoring-apis/assets-api](https://docs.kubecost.com/apis/monitoring-apis/assets-api)

#### Tags

- Assets, Kubernetes, Monitoring

#### Properties

- [Documentation](https://docs.kubecost.com/apis/monitoring-apis/assets-api)
- [OpenAPI](openapi/kubecost-assets-openapi.yml)
- [JSONSchema](json-schema/asset.json)
- [JSONLD](json-ld/kubecost-context.jsonld)

### Kubecost Cloud Cost API

The Cloud Cost API provides accurate cost information from your cloud service providers (CSPs), including AWS, Azure, and GCP. It offers multiple endpoints for querying, aggregating, and analyzing cloud costs.

**Human URL:** [https://docs.kubecost.com/apis/monitoring-apis/cloud-cost-api](https://docs.kubecost.com/apis/monitoring-apis/cloud-cost-api)

#### Tags

- AWS, Azure, Cloud Cost, GCP, Monitoring

#### Properties

- [Documentation](https://docs.kubecost.com/apis/monitoring-apis/cloud-cost-api)
- [OpenAPI](openapi/kubecost-cloud-cost-openapi.yml)
- [JSONSchema](json-schema/cloud-cost.json)
- [JSONLD](json-ld/kubecost-context.jsonld)

### Kubecost Budget API

The Budget API allows you to create, update, and delete recurring budget rules to control your Kubernetes spending. Weekly and monthly budgets can be established on workloads to set limits on cost spend, with the option to configure alerts for reaching specified budget thresholds via email, Slack, or Microsoft Teams.

**Human URL:** [https://docs.kubecost.com/apis/governance-apis/budget-api](https://docs.kubecost.com/apis/governance-apis/budget-api)

#### Tags

- Budget, Governance, Spending

#### Properties

- [Documentation](https://docs.kubecost.com/apis/governance-apis/budget-api)
- [OpenAPI](openapi/kubecost-budget-openapi.yml)
- [JSONSchema](json-schema/budget.json)
- [JSONSchema](json-schema/budget-action.json)
- [JSONLD](json-ld/kubecost-context.jsonld)

### Kubecost Forecast API

The Forecast API provides cost forecasting capabilities for Kubernetes workloads, allowing you to predict future spend based on historical cost data and trends.

**Human URL:** [https://docs.kubecost.com/apis/governance-apis/forecast-api](https://docs.kubecost.com/apis/governance-apis/forecast-api)

#### Tags

- Cost Prediction, Forecast, Governance

#### Properties

- [Documentation](https://docs.kubecost.com/apis/governance-apis/forecast-api)
- [OpenAPI](openapi/kubecost-forecast-openapi.yml)
- [JSONSchema](json-schema/forecast.json)
- [JSONLD](json-ld/kubecost-context.jsonld)

### Kubecost Savings API

The Savings APIs provide cost optimization insights, including cluster-level potential savings estimates, recommendations for right-sizing clusters and containers, listing abandoned workloads, orphaned disks, and orphaned IP addresses.

**Human URL:** [https://docs.kubecost.com/apis/savings-apis](https://docs.kubecost.com/apis/savings-apis)

#### Tags

- Optimization, Right-Sizing, Savings

#### Properties

- [Documentation](https://docs.kubecost.com/apis/savings-apis)
- [OpenAPI](openapi/kubecost-savings-openapi.yml)
- [JSONSchema](json-schema/savings-recommendation.json)
- [JSONLD](json-ld/kubecost-context.jsonld)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
