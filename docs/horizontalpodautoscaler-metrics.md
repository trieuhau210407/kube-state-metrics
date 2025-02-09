# Horizontal Pod Autoscaler Metrics

| Metric name                       | Metric type | Labels/tags                                                   | Status |
| --------------------------------  | ----------- | ------------------------------------------------------------- | ------ |
| kube_horizontalpodautoscaler_info                     | Gauge       | `horizontalpodautoscaler`=&lt;hpa-name&gt; <br> `namespace`=&lt;hpa-namespace&gt; <br> `scaletargetref_api_version`=&lt;hpa-target-api-version&gt; <br> `scaletargetref_kind`=&lt;hpa-target-kind&gt; <br> `scaletargetref_name`=&lt;hpa-target-name&gt; | EXPERIMENTAL |
| kube_horizontalpodautoscaler_annotations              | Gauge       | `horizontalpodautoscaler`=&lt;hpa-name&gt; <br> `namespace`=&lt;hpa-namespace&gt; | EXPERIMENTAL |
| kube_horizontalpodautoscaler_labels                   | Gauge       | `horizontalpodautoscaler`=&lt;hpa-name&gt; <br> `namespace`=&lt;hpa-namespace&gt; | STABLE |
| kube_horizontalpodautoscaler_metadata_generation      | Gauge       | `horizontalpodautoscaler`=&lt;hpa-name&gt; <br> `namespace`=&lt;hpa-namespace&gt; | STABLE |
| kube_horizontalpodautoscaler_spec_max_replicas        | Gauge       | `horizontalpodautoscaler`=&lt;hpa-name&gt; <br> `namespace`=&lt;hpa-namespace&gt; | STABLE |
| kube_horizontalpodautoscaler_spec_min_replicas        | Gauge       | `horizontalpodautoscaler`=&lt;hpa-name&gt; <br> `namespace`=&lt;hpa-namespace&gt; | STABLE |
| kube_horizontalpodautoscaler_spec_target_metric       | Gauge       | `horizontalpodautoscaler`=&lt;hpa-name&gt; <br> `namespace`=&lt;hpa-namespace&gt; <br> `metric_name`=&lt;metric-name&gt; <br> `metric_target_type`=&lt;value\|utilization\|average&gt; | EXPERIMENTAL |
| kube_horizontalpodautoscaler_status_condition         | Gauge       | `horizontalpodautoscaler`=&lt;hpa-name&gt; <br> `namespace`=&lt;hpa-namespace&gt; <br> `condition`=&lt;hpa-condition&gt; <br> `status`=&lt;true\|false\|unknown&gt; | STABLE |
| kube_horizontalpodautoscaler_status_current_replicas  | Gauge       | `horizontalpodautoscaler`=&lt;hpa-name&gt; <br> `namespace`=&lt;hpa-namespace&gt; | STABLE |
| kube_horizontalpodautoscaler_status_desired_replicas  | Gauge       | `horizontalpodautoscaler`=&lt;hpa-name&gt; <br> `namespace`=&lt;hpa-namespace&gt; | STABLE |
| kube_horizontalpodautoscaler_status_current_metric    | Gauge       | `horizontalpodautoscaler`=&lt;hpa-name&gt; <br> `namespace`=&lt;hpa-namespace&gt; <br> `metric_name`=&lt;metric-name&gt; <br> `metric_target_type`=&lt;metric-target-type&gt;  | EXPERIMENTAL |
