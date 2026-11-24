---
layout: course
title: CENG205 Data Structures (Lab)
description: Laboratory sessions of the undergraduate Data Structures course, covering memory management, algorithm analysis, stacks, queues, linked lists, trees and graphs with hands-on C programming.
year: 2025
term: 2025–2026 Fall
course_id: ceng205-data-structures-lab
schedule:
  - week: 1
    topic: Pointers, Dynamic Memory, Stack vs. Heap
    description: Data types and abstract data types, pointers, dynamic memory allocation and the differences between stack and heap memory.
    materials:
      - name: Slides
        url: /assets/teaching/ceng205-2025-fall/week01-slides.pdf

  - week: 2
    topic: Memory Model, Recursion, Searching and Sorting
    description: How function calls use the stack, recursion, binary search and selection sort.
    materials:
      - name: Slides
        url: /assets/teaching/ceng205-2025-fall/week02-slides.pdf
      - name: Iterative Binary Search
        url: /assets/teaching/ceng205-2025-fall/week02-iterative-binary-search.txt
      - name: Recursive Binary Search
        url: /assets/teaching/ceng205-2025-fall/week02-recursive-binary-search.txt
      - name: Selection Sort
        url: /assets/teaching/ceng205-2025-fall/week02-selection-sort.txt

  - week: 3
    topic: Big-O Notation
    description: Asymptotic analysis and analyzing the complexity of code.
    materials:
      - name: Slides
        url: /assets/teaching/ceng205-2025-fall/week03-slides.pdf

  - week: 4
    topic: Complexity Exercises and Matrices
    description: Comparing growth rates with exercises, and matrix representations such as triangular matrices.
    materials:
      - name: Slides
        url: /assets/teaching/ceng205-2025-fall/week04-slides.pdf

  - week: 5
    topic: Stacks and Queues
    description: Stack and queue as abstract data types, and circular queues.
    materials:
      - name: Slides
        url: /assets/teaching/ceng205-2025-fall/week05-slides.pdf
      - name: Queue
        url: /assets/teaching/ceng205-2025-fall/week05-queue.txt
      - name: Circular Queue
        url: /assets/teaching/ceng205-2025-fall/week05-circular-queue.txt
      - name: Stack with Strings
        url: /assets/teaching/ceng205-2025-fall/week05-string.txt
      - name: Stack with a Word Array
        url: /assets/teaching/ceng205-2025-fall/week05-string-array.txt

  - week: 6
    topic: Midterm Exam Week
    description: No lab session.

  - week: 7
    topic: Infix, Prefix and Postfix Notation
    description: Expression notations and converting infix expressions to postfix with a stack.
    materials:
      - name: Slides
        url: /assets/teaching/ceng205-2025-fall/week07-slides.pdf
      - name: Infix to Postfix
        url: /assets/teaching/ceng205-2025-fall/week07-infix-to-postfix.txt

  - week: 8
    topic: Stack Exercises and Recursion
    description: Push and pop sequence exercises and recursion examples.
    materials:
      - name: Slides
        url: /assets/teaching/ceng205-2025-fall/week08-slides.pdf

  - week: 9
    topic: Stack Exercises and Recursion (continued)
    description: Continuation of the week 8 topics.

  - week: 10
    topic: Singly Linked Lists
    description: Insertion and deletion in singly linked and circular linked lists.
    materials:
      - name: Insertion
        url: /assets/teaching/ceng205-2025-fall/week10-singly-linked-insert.txt
      - name: Deletion
        url: /assets/teaching/ceng205-2025-fall/week10-singly-linked-delete.txt
      - name: Circular List Deletion
        url: /assets/teaching/ceng205-2025-fall/week10-circular-linked-delete.txt

  - week: 11
    topic: Doubly Linked Lists and Dummy Nodes
    description: Insertion in doubly linked lists and deletion in circular lists with a dummy node.
    materials:
      - name: Doubly Linked Insertion
        url: /assets/teaching/ceng205-2025-fall/week11-doubly-linked-insert.txt
      - name: Circular Deletion with Dummy Node
        url: /assets/teaching/ceng205-2025-fall/week11-circular-linked-delete-dummy.txt

  - week: 12
    topic: Binary Search Trees
    description: Insertion and deletion in binary search trees.
    materials:
      - name: BST Insertion
        url: /assets/teaching/ceng205-2025-fall/week12-bst-insert.txt
      - name: BST Deletion
        url: /assets/teaching/ceng205-2025-fall/week12-bst-delete.txt

  - week: 13
    topic: Binary Search Trees (continued)
    description: Continuation of the week 12 topics.

  - week: 14
    topic: Graphs
    description: Graph definitions and representing graphs with adjacency matrices and adjacency lists.
    materials:
      - name: Slides
        url: /assets/teaching/ceng205-2025-fall/week14-slides.pdf
---
<style>
:root { --global-theme-color: #402599; --global-hover-color: #1C1338; }
html[data-theme="dark"] { --global-theme-color: #402599; --global-hover-color: #1C1338; }
a, a:visited { color: var(--global-theme-color); }
a:hover { color: var(--global-hover-color); }
/* no session dates are listed, so hide the empty Date column */
.course table th:nth-child(2), .course table td:nth-child(2) { display: none; }
</style>

<img src="{{ '/assets/teaching/ceng205-2025-fall/data-structures-banner.png' | relative_url }}" alt="Array, linked list, stack and binary search tree diagrams" class="img-fluid" style="margin: 0.5rem 0 1.5rem 0;">

**Role:** Lab Teaching Assistant

Slides and C code examples I prepared for the weekly lab sessions. Slides are in Turkish and English.
