---
title: '&lt;numeric&gt; | Microsoft Docs'
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: article
f1_keywords:
- std::<numeric>
- std.<numeric>
- <numeric>
dev_langs:
- C++
helpviewer_keywords:
- <numeric> header
ms.assetid: 6d6ccb94-48cc-479b-b4a9-bd9c78d4896a
caps.latest.revision: 23
author: corob-msft
ms.author: corob
manager: ghogen
translation.priority.ht:
- cs-cz
- de-de
- es-es
- fr-fr
- it-it
- ja-jp
- ko-kr
- pl-pl
- pt-br
- ru-ru
- tr-tr
- zh-cn
- zh-tw
translationtype: Human Translation
ms.sourcegitcommit: 2d05749ba2837a3879c91886b9266de47dd2ece6
ms.openlocfilehash: 9cb8631899ee9fdeec6f929b37e99c16399e29c7

---
# &lt;numeric&gt;
Defines container template functions that perform algorithms for numerical processing.  
  
## Syntax  
  
```  
#include <numeric>  
```  
  
## Remarks  
 The algorithms resemble the Standard Template Library (STL) algorithms, but are part of the C++ Standard Library instead. Nevertheless, they are compatible with the STL and, like the STL algorithms, they can operate on a variety of data structures. These include STL container classes—for example, [vector](../standard-library/vector-class.md) and [list](../standard-library/list-class.md), and program-defined data structures and arrays of elements that satisfy the requirements of a particular algorithm. The algorithms achieve this level of generality by accessing and traversing the elements of a container indirectly through iterators. The algorithms process iterator ranges that are typically specified by their beginning or ending positions. The ranges referred to must be valid in the sense that all pointers in the ranges must be dereferenceable and within the sequences of each range, and the last position must be reachable from the first by means of incrementation.  
  
 The algorithms extend the actions that are supported by the operations and member functions of each of the STL containers and enable interaction with different types of container objects at the same time.  
  
### Functions  
  
|||  
|-|-|  
|[accumulate](../standard-library/numeric-functions.md#accumulate)|Computes the sum of all elements in a specified range—including some initial value—by computing successive partial sums, or computes the result of successive partial results that are obtained by using a specified binary operation instead of the sum operation.|  
|[adjacent_difference](../standard-library/numeric-functions.md#adjacent_difference)|Computes the successive differences between each element and its predecessor in an input range and outputs the results to a destination range, or computes the result of a generalized procedure where the difference operation is replaced by another specified binary operation.|  
|[inner_product](../standard-library/numeric-functions.md#inner_product)|Computes the sum of the element-wise product of two ranges and adds it to a specified initial value, or computes the result of a generalized procedure where the sum and product operations are replaced by other specified binary operations.|  
|[iota](../standard-library/numeric-functions.md#iota)|Stores a starting value, beginning with the first element and filling with successive increments of the value (`value++`) in each of the elements in the interval `[first, last)`.|  
|[partial_sum](../standard-library/numeric-functions.md#partial_sum)|Computes a series of sums in an input range from the first element through the *i*th element and stores the result of each sum in the *i*th element of a destination range, or computes the result of a generalized procedure where the sum operation is replaced by another specified binary operation.|  
  
## See Also  
 [Header Files Reference](../standard-library/cpp-standard-library-header-files.md)   
 [Thread Safety in the C++ Standard Library](../standard-library/thread-safety-in-the-cpp-standard-library.md)   
 [C++ Standard Library Reference](../standard-library/cpp-standard-library-reference.md)




<!--HONumber=Jan17_HO2-->


