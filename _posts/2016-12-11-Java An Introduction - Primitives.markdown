---
layout:     post
title:      "Java An Introduction: "
subtitle:   "Primitives"
date:       2016-12-11 12:00:00
author:     "Chris Coverdale"
header-img: "img/post-bg-primitives2.jpg"
tags:       ["Java", "Fundamentals"]
---
<h2 class="section-heading">The Primitives</h2>
<p>There are 8 primitive data types in the Java language. Understanding these data types is important.</p>

<p>The 8 primitive types:
   <ul>
  <li>boolean</li>
  <li>byte</li>
  <li>short</li>
  <li>char</li>
  <li>int</li>
  <li>long</li>
  <li>float</li>
  <li>double</li>
  </ul></p>

<p>Okay, so we know the names of these data types but what actually are they?</p>
<p>To start us off we should look at the two smallest data types, the bit and the byte.</p>

<h2 class="section-heading">Bits and Bytes</h2>

<div class="centerImage"><img src="{{ site.baseurl }}/img/post-sample-biting.jpg" alt="Post Sample Image" ><span class="caption text-muted">Hmmmm not quiet...</span></div>

<p>A bit is the smallest unit of data it is a single binary value that is either 0 or 1. The bit is the first building block.</p>

<p><h4>Byte:</h4> A byte is a fundamental unit of memory, it consists of 8 bits. In Java, bytes are used to save digits in memory.
<ul>
<li>Minimum value: -128</li>
<li>Maximum value: 127</li>
<li>Why Bytes? Bytes are an excellent data type to save storage space when using small number in Arrays. Since a byte only needs enough space to hold digits between -128 to 127</li>
</ul>

<p><h4>Short:</h4> A short is a 16-bit data type. It's double the size of a byte.
<ul>
<li>Minimum value: -32,768</li>
<li>Maximum value: 32,767</li>
<li>Why Shorts? Again, shorts are small data types, not requiring any more space than needed to hold a digit.</li>
</ul>

<p><h4>Int:</h4> An int is probably the most well-known data types across programming languages. The int is a 32-bit data type. It is the default value for digits used unless there are specific memory related requirements.
<ul>
<li>Minimum value: -2,147,483,648</li>
<li>Maximum value: 2,147,483,647 </li>
<li>Why Int? The most widely recognized data type and can hold fairly large digits in memory.</li>
</ul>

<p><h4>Long:</h4> Now we are dealing with the big boys. The long data type is twice the size of an int. Long is a 64-bit data type.
<ul>
<li>Minimum value: -9,223,372,036,854,775,808</li>
<li>Maximum value: 9,223,372,036,854,775,807</li>
<li>Why long? Used if the number range is greater than the int range.</li>
</ul>

<p><h4>Float:</h4> Floats are values that have a decimal point after a digit. Floats are  single-precision 32-bit IEEE 754.
<ul>
<li>Minimum value: -9,223,372,036,854,775,808</li>
<li>Maximum value: 9,223,372,036,854,775,807</li>
<li>Why float? To use numbers with decimal points.</li>
</ul>

<p><h4>Double:</h4> Doubles are twice the size of a float. Doubles are double-precision 64-bit IEEE 754.
<ul>
<li>Minimum value: -9,223,372,036,854,775,808</li>
<li>Maximum value: 9,223,372,036,854,775,807</li>
<li>Why double? Doubles tend to be the default data-type when dealing with decimal digits.</li>
</ul>

<p><h4>Char:</h4> Char's refer to uni-code characters. Uni-code characters include alphabets and common symbols such as (?, %, $, #, @ and more...). Char data-types are 16-bit.
<ul>
<li>Why char? For any values that are not digits.</li>
</ul>

<p><h4>Boolean:</h4> I saved the smallest for last. The Boolean is 1 bit. It has only two possible values 0 (False) or 1 (True).
<ul>
<li>boolean a = false;</li>
<li>boolean b = true;</li>
<li>Why boolean? Booleans are important in creating logical flows in programs.</li>
</ul>
