# C# Quick Guides

A set of 14 self-contained, single-file HTML quick-reference guides covering introductory C# and object-oriented programming, from a first "Hello World" program through files, streams, and event-driven GUI applications. Each guide is comprehensive, exam-aligned, and safe to hand directly to students: every code example is original rather than pulled from any test bank.

Built and verified against **Visual Studio 2026 / .NET 10 / C# 14**.

## Getting Started

1. Download or clone this repository.
2. Open `index.html` in any modern browser, or host the folder with GitHub Pages / any static file host.
3. Click a guide card on the index page to open that guide in a new tab.

No build step, server, or dependency installation is required. Every page is a single static HTML file with inline CSS and a small inline script; the only external resources are Google Fonts (Fira Code, Source Sans Pro, Merriweather) loaded over a CDN link.

## Repository Structure

```
.
├── index.html                                   # Landing page linking to all 14 guides
├── cs-guide1-intro-to-oop.html
├── cs-guide2-using-data.html
├── cs-guide3-gui-vs-ide.html
├── cs-guide4-making-decisions.html
├── cs-guide5-looping.html
├── cs-guide6-using-arrays.html
├── cs-guide7-using-methods.html
├── cs-guide8-advanced-methods.html
├── cs-guide9-classes-and-objects.html
├── cs-guide10-introduction-to-inheritance.html
├── cs-guide11-exception-handling.html
├── cs-guide12-using-controls.html
├── cs-guide13-handling-events.html
├── cs-guide14-files-and-streams.html
└── assets/
    └── favicon.png                              # Shared favicon referenced by every page
```

> **Note:** `assets/favicon.png` must be present in the repository for the favicon links in `index.html` and each guide to resolve. Add your own PNG at that path (any square icon works).

## The Guides

| # | Guide | Topics Covered |
|---|-------|-----------------|
| 1 | [Introduction to Object-Oriented Programming](cs-guide1-intro-to-oop.html) | The programming process, procedural vs. object-oriented programming, classes and objects, encapsulation, inheritance, polymorphism, identifiers, comments, namespaces, and compiling C# programs |
| 2 | [Using Data](cs-guide2-using-data.html) | Variables and constants, intrinsic data types, console output and formatting, arithmetic and comparison operators, type conversion, characters and strings, enumerations, and console input |
| 3 | [Using GUI Objects and the Visual Studio IDE](cs-guide3-gui-vs-ide.html) | The Visual Studio IDE, forms and controls, properties, fonts, events and methods, focus and tab order, formatting GUI output, design time vs. runtime, refactoring, and console vs. GUI applications |
| 4 | [Making Decisions](cs-guide4-making-decisions.html) | Planning program logic, single- and dual-alternative decisions, compound AND/OR expressions and short-circuit evaluation, logical vs. conditional operators, switch structures, the ternary operator, negation, and decision-making best practices |
| 5 | [Looping](cs-guide5-looping.html) | Loop fundamentals, while loops, for loops, do loops, pretest vs. posttest loops, nested loops, accumulating totals, scope, loop optimization, and loops in GUI applications |
| 6 | [Using Arrays](cs-guide6-using-arrays.html) | Declaring and initializing arrays, accessing elements, the foreach loop, searching arrays, parallel arrays and range matches, built-in array methods, multidimensional and jagged arrays, and arrays in GUI applications |
| 7 | [Using Methods](cs-guide7-using-methods.html) | Method fundamentals, method structure, accessibility and static modifiers, scope, formal parameters and arguments, return values, passing arrays by value and by reference, Main() method variations, and methods in GUI applications |
| 8 | [Advanced Method Concepts](cs-guide8-advanced-methods.html) | Value vs. reference parameters, mandatory and optional parameters, ref and out parameters, parameter arrays (params), returning references, method overloading, overload resolution and betterness rules, ambiguous methods, and named and optional arguments |
| 9 | [Using Classes and Objects](cs-guide9-classes-and-objects.html) | Class fundamentals, access modifiers, composition, instantiation and reference types, properties, the this reference, constructors and constructor initializers, object initializers, operator overloading, arrays of objects and IComparable, interfaces, and destructors |
| 10 | [Introduction to Inheritance](cs-guide10-introduction-to-inheritance.html) | Inheritance basics, protected access, polymorphism and overriding, implicit reference conversions, the Object class, base class constructors, abstract and sealed classes, interfaces and multiple inheritance, extension methods, and GUI inheritance |
| 11 | [Exception Handling](cs-guide11-exception-handling.html) | Exception fundamentals and the exception hierarchy, object-oriented error handling, common built-in exception types, try/catch structure and multiple catch blocks, Exception class members, TryParse() methods, the finally block, the call stack and propagation, and custom exceptions |
| 12 | [Using Controls](cs-guide12-using-controls.html) | Control fundamentals and IDE-generated code, fonts, color and accessibility, CheckBox and RadioButton selection controls, grouping with GroupBox and Panel, PictureBox graphics, list controls, date/time controls, multiple forms and navigation, form layout, and menus |
| 13 | [Handling Events](cs-guide13-handling-events.html) | Event-driven architecture, delegates and composed delegates, custom and built-in event handlers, control component events, mouse events, keyboard events, and managing focus and shared handlers across multiple controls |
| 14 | [Files and Streams](cs-guide14-files-and-streams.html) | Storage fundamentals, files and paths, the File and Directory classes, the data hierarchy, sequential vs. random access files, streams and file-processing classes, reading and writing text files with delimiters and tokens, searching files with the file position pointer and Seek(), and serialization |

## Design System

Every guide shares the same layout and typography for a consistent reading experience, while each one gets its own accent color so students can tell guides apart at a glance:

- **Typography:** Merriweather for headings, Source Sans Pro for body text, Fira Code for code blocks (with font ligatures explicitly disabled so operators like `!=`, `>=`, and `<=` render as plain characters).
- **Layout:** A sticky header with jump-to-section navigation pills, an intro banner, concept cards, comparison panels, tip/warning/success callout boxes, syntax boxes with syntax-highlighted code, and a dark "quick reference" summary table at the end of each guide.
- **Dynamic header offset:** A small inline script measures the sticky header's actual rendered height (which varies as the nav pills wrap across screen sizes) and feeds it into each section heading's `scroll-margin-top`, so in-page navigation links always land just below the header instead of underneath it.
- **Accent colors:** Purple, emerald, amber, rose, blue, teal, fuchsia, lime, slate, indigo, sky blue, burnt orange, cyan, and mustard yellow, one per guide, in the order listed in the table above.

## Content Notes

- All code examples throughout the guides are original and were written specifically for these guides; none are copied from any test, quiz, or assignment.
- Guide content is organized thematically (by concept), not in the same order questions may appear on any given assessment, so guides are best used as reference material and studied in full rather than searched question-by-question.
- No guide refers to a specific textbook, edition, or chapter number; all content is self-contained.

## License

Internal course material. Adapt freely for your own classroom use.
