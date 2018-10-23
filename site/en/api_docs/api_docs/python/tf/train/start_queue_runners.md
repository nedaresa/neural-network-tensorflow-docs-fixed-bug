

page_type: reference


<!-- DO NOT EDIT! Automatically generated file. -->


# tf.train.start_queue_runners

### Aliases:

* `tf.train.queue_runner.start_queue_runners`
* `tf.train.start_queue_runners`

``` python
start_queue_runners(
    sess=None,
    coord=None,
    daemon=True,
    start=True,
    collection=tf.GraphKeys.QUEUE_RUNNERS
)
```



Defined in [`tensorflow/python/training/queue_runner_impl.py`](https://www.github.com/tensorflow/tensorflow/blob/r1.4/tensorflow/python/training/queue_runner_impl.py).

See the guides: [Reading data > Reading from files](../../../../api_guides/python/reading_data#Reading_from_files), [Threading and Queues > Queue usage overview](../../../../api_guides/python/threading_and_queues#Queue_usage_overview), [Training > Coordinator and QueueRunner](../../../../api_guides/python/train#Coordinator_and_QueueRunner)

Starts all queue runners collected in the graph.

This is a companion method to `add_queue_runner()`.  It just starts
threads for all queue runners collected in the graph.  It returns
the list of all threads.

#### Args:

* <b>`sess`</b>: `Session` used to run the queue ops.  Defaults to the
    default session.
* <b>`coord`</b>: Optional `Coordinator` for coordinating the started threads.
* <b>`daemon`</b>: Whether the threads should be marked as `daemons`, meaning
    they don't block program exit.
* <b>`start`</b>: Set to `False` to only create the threads, not start them.
* <b>`collection`</b>: A `GraphKey` specifying the graph collection to
    get the queue runners from.  Defaults to `GraphKeys.QUEUE_RUNNERS`.


#### Raises:

* <b>`ValueError`</b>: if `sess` is None and there isn't any default session.
* <b>`TypeError`</b>: if `sess` is not a `tf.Session` object.


#### Returns:

A list of threads.