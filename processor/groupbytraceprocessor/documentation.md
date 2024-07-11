[comment]: <> (Code generated by mdatagen. DO NOT EDIT.)

# groupbytrace

## Internal Telemetry

The following telemetry is emitted by this component.

### processor_groupbytrace_conf_num_traces

Maximum number of traces to hold in the internal storage

| Unit | Metric Type | Value Type |
| ---- | ----------- | ---------- |
| 1 | Gauge | Int |

### processor_groupbytrace_event_latency

How long the queue events are taking to be processed

| Unit | Metric Type | Value Type |
| ---- | ----------- | ---------- |
| ms | Histogram | Int |

### processor_groupbytrace_incomplete_releases

Releases that are suspected to have been incomplete

| Unit | Metric Type | Value Type | Monotonic |
| ---- | ----------- | ---------- | --------- |
| <nil> | Sum | Int | true |

### processor_groupbytrace_num_events_in_queue

Number of events currently in the queue

| Unit | Metric Type | Value Type |
| ---- | ----------- | ---------- |
| 1 | Gauge | Int |

### processor_groupbytrace_num_traces_in_memory

Number of traces currently in the in-memory storage

| Unit | Metric Type | Value Type |
| ---- | ----------- | ---------- |
| 1 | Gauge | Int |

### processor_groupbytrace_spans_released

Spans released to the next consumer

| Unit | Metric Type | Value Type | Monotonic |
| ---- | ----------- | ---------- | --------- |
| 1 | Sum | Int | true |

### processor_groupbytrace_traces_evicted

Traces evicted from the internal buffer

| Unit | Metric Type | Value Type | Monotonic |
| ---- | ----------- | ---------- | --------- |
| 1 | Sum | Int | true |

### processor_groupbytrace_traces_released

Traces released to the next consumer

| Unit | Metric Type | Value Type | Monotonic |
| ---- | ----------- | ---------- | --------- |
| 1 | Sum | Int | true |