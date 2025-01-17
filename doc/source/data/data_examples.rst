.. _data-examples-ref:

=================
Ray Data Examples
=================

.. tip:: Check out the Datasets :ref:`User Guide <data_user_guide>` to learn more about
  Dataset features in-depth.

.. _data-recipes:

Ray Data is a data processing engine that supports multiple data
modalities and types. Here you will find a few end-to-end examples of some basic data
processing with Ray Data on tabular data, text (coming soon), and images.

Computer Vision
---------------
.. grid:: 1 2 2 3
    :gutter: 1
    :class-container: container pb-4

    .. grid-item-card::

       .. button-ref:: examples/huggingface_vit_batch_prediction

            Image Classification Batch Inference with Huggingface Vision Transformer


    .. grid-item-card::

       .. button-ref:: examples/pytorch_resnet_batch_prediction

            Image Classification Batch Inference with PyTorch ResNet18

    
    .. grid-item-card::

        .. button-ref:: examples/batch_inference_object_detection

            Object Detection Batch Inference with PyTorch FasterRCNN_ResNet50


Simple Data Processing
----------------------

.. grid:: 1 2 3 3
    :gutter: 2
    :class-container: container pb-4

    .. grid-item-card::

        .. button-ref:: examples/nyc_taxi_basic_processing

            Processing the NYC taxi dataset

    .. grid-item-card::

        .. button-ref:: examples/batch_training

            Batch Training with Ray Data

    .. grid-item-card::

        .. button-ref:: examples/ocr_example

            Scaling OCR with Ray Data



Other Examples
--------------


.. grid:: 1 2 3 3
    :gutter: 2
    :class-container: container pb-4

    .. grid-item-card::

        .. button-ref:: examples/random-access

            Random Data Access (Experimental)

    .. grid-item-card::

        .. button-ref:: examples/custom-datasource

            Implementing a Custom Datasource
