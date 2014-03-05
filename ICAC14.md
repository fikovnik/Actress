---
layout: docs
title: ICAC'14 Companion Web Page
---

This pages contains supplementary XFCDL source of the adaptation scenarios described in our ICAC'14 submission.

The complete FCDL and ACTRESS documentation is available in the [technical report](FCDL.pdf) (F. Krikava and P.Collet Feedback Control Definition Language. Technical report, I3S CNRS - UMR 7271, 2013).

## Preliminary

* [commons.xfcdl](ICAC14/commons/commons.xfcdl)
    * FileTailer
    * FileReader
    * Hostname
    * IController
    * Tuple2
    * Queue
    * MapStore
    * MapMaxKey
    * MapAvgValue
    * EventBusSubscriber
    * EventBusPublisher
    * FileWriter
    * Accumulator
    * SineWave
    * PeriodicTrigger

## Local Content Delivery Adaptation

<img src="ICAC14/LocalContentDelivery.png" style="width: 100%;"/>

* [ApacheQOS.xfcdl](ICAC14/cs1/ApacheQOS.xfcdl)
    * ApacheQOS
* [QOSControl.xfcdl](ICAC14/cs1/QOSControl.xfcdl)
    * LoadMonitor
    * QOSControl
* [ApacheWebServer.xfcdl](ICAC14/cs1/ApacheWebServer.xfcdl)
    * AccessLogParser
    * ApacheWebServer

## Distributed Content Delivery Adaptation

<img src="ICAC14/LocalApacheQOS.png" style="width: 70%;"/>
<img src="ICAC14/DistributedContentDelivery.png" style="width: 70%;"/>

* [ApacheQOS.xfcdl](ICAC14/cs2/ApacheQOS.xfcdl)
    * ApacheQOS
* [LocalApacheQOS.xfcdl](ICAC14/cs2/LocalApacheQOS.xfcdl)
	* LocalApacheQOS
* [LoadBalancerControl.xfcdl](ICAC14/cs2/LocalApacheControl.xfcdl)
    * LoadBalancerController
    * LoadBalancerControl

## Distributed Resource Management

<img src="ICAC14/DistributedResourceManagement.png" style="width: 70%;"/>

* [ServerPoolControl.xfcdl](ICAC14/cs2/ServerPoolControl.xfcdl)
    * ServerPoolControl

## System Identification

<img src="ICAC14/SystemIdentification.png" style="width: 70%;"/>

* [SystemIdentification.xfcdl](ICAC14/cs3/SystemIdentification.xfcdl)
    * UtilizationMonitor
    * SystemIdentification

## Adaptive Control

<img src="ICAC14/AdaptiveControl.png" style="width: 100%;"/>

* [AdaptiveApacheQOS.xfcdl](ICAC14/cs4/AdaptiveApacheQOS.xfcdl)
    * AdaptiveApacheQOS
* [QOSControl.xfcdl](ICAC14/cs4/QOSControl.xfcdl)
    * QOSControl
* [AdaptiveControl.xfcdl](ICAC14/cs4/AdaptiveControl.xfcdl)
    * AdaptiveControl
    * AdaptiveController