# Advanced HTML

This document provides a step-by-step guide on how to use and work with HTML (HyperText Markup Language). HTML is the standard language for creating web pages. Below are the basic steps to get started with HTML, followed by a tasks section for practice exercises.

## Table of Contents

- [Advanced HTML](#advanced-html)
  - [Table of Contents](#table-of-contents)
  - [What is HTML](#what-is-html)
  - [Basic Structure of an HTML Document](#basic-structure-of-an-html-document)
  - [Description `HTML` Code Commands](#description-html-code-commands)
    - [Common HTML Tags](#common-html-tags)
  - [Example](#example)
  - [Text Formatting](#text-formatting)
  - [Links and Images](#links-and-images)
- [Tasks](#tasks)

## What is HTML

HTML (HyperText Markup Language) is the standard language used to create documents that can be displayed in a web browser. HTML describes the structure of a web page using elements and tags.

## Basic Structure of an HTML Document

The basic structure of an HTML document includes the following elements:

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Page Title</title>
    </head>
    <body>
        <h1>Main Heading</h1>
        <p>This is a sample paragraph.</p>
    </body>
    </html>

## Description `HTML` Code Commands

`<!DOCTYPE html>`: Declares the document type and version of HTML.

`<html>`: The root element that contains the entire content of the page.

`<head>`: Contains metadata and links to external resources like CSS and JavaScript.

`<title>`: The title of the page displayed in the browser tab.

`<body>`: Contains the visible content of the web page.

### Common HTML Tags

Some common HTML tags include:

`<h1>` to `<h6>`: Headings of different levels.

`<p>`: Paragraph.

`<a>`: Link.

`<img>`: Image.

`<ul>`, `<ol>`, `<li>`: Unordered and ordered lists.

`<table>`, `<tr>`, `<th>`, `<td>`: Tables.

HTML Attributes
Attributes provide additional information about HTML elements. They are written inside the opening tag.

## Example

    <a href="https://www.example.com" target="_blank">Visit Example</a>

    <img src="path/to/image.jpg" alt="Image description" width="500" height="300">

## Text Formatting

Tags for text formatting:

`<b>`: Bold.

`<i>`: Italic.

`<u>`: Underline.

`<br>`: Line break.

`<mark>`: Highlight.

## Links and Images

Links
Links allow navigation between web pages.

    <a href="https://www.example.com">Visit Example</a>

Images

To insert an image:

    <img src="path/to/image.jpg" alt="Image description">

Lists

Unordered Lists:

    <ul>
        <li>Item 1</li>
        <li>Item 2</li>
        <li>Item 3</li>
    </ul>

Ordered Lists

    <ol>
        <li>Item 1</li>
        <li>Item 2</li>
        <li>Item 3</li>
    </ol>

Tables

Tables are used to organize data in rows and columns.

    <table>
        <thead>
            <tr>
                <th>Header 1</th>
                <th>Header 2</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Data 1</td>
                <td>Data 2</td>
            </tr>
            <tr>
                <td>Data 3</td>
                <td>Data 4</td>
            </tr>
        </tbody>
    </table>

Forms

Forms collect user input.

    <form action="/submit-data" method="post">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name">
        <input type="submit" value="Submit">
    </form>

Multimedia

Videos

    <video src="path/to/video.mp4" controls autoplay loop poster="path/to/poster.jpg">
        Your browser does not support the video tag.
    </video>

Iframes

    <iframe src="https://www.example.com" width="600" height="400" frameborder="0" allowfullscreen></iframe>

# Tasks

1- [0. Create your first webpage](#0-index.html)
