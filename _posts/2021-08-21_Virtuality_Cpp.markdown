---
layout: post
title:  "C++ virtual methods"
date:   2021-08-21 09:54:21 +0200
categories: cpp
---
# Introduction

One of the technical options to support polymorphie in C++ are virtual methods. This blog post gives an overview of how to use them, how they are implemented by compilers and what are the performance implications of using them.

## Small example

class Shape
{
    virtual double caculateSize() = 0;
    virtual ~Shape()=default;
};

# Ressources
* [the bpftrace program for udp_sendto latency tracing](https://github.com/matkonnerth/bpfExamples/blob/master/udp_sendto.bt)
