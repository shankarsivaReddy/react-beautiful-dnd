# React-beautiful-dnd
## link- https://www.npmjs.com/package/react-beautiful-dnd
## videolink - https://egghead.io/lessons/react-create-reorderable-horizontal-lists-with-react-beautiful-dnd-direction-prop

react-beautiful-dnd (rbd)

Beautiful and accessible drag and drop for lists with React

CircleCI branch npm

quote application example

Play with this example if you want!

Core characteristics

Beautiful and natural movement of items 💐

Accessible: powerful keyboard and screen reader support ♿️

Extremely performant 🚀

Clean and powerful api which is simple to get started with

Plays extremely well with standard browser interactions

Unopinionated styling

No creation of additional wrapper dom nodes - flexbox and focus management friendly!

Get started 👩‍🏫

We have created a free course on egghead.io 🥚 to help you get started with react-beautiful-dnd as quickly as possible.

course-logo

Currently supported feature set ✅

Vertical lists ↕

Horizontal lists ↔

Movement between lists (▤ ↔ ▤)

Virtual list support 👾 - unlocking 10,000 items @ 60fps

Combining items

Mouse 🐭, keyboard 🎹♿️ and touch 👉📱 (mobile, tablet and so on) support

Multi drag support

Incredible screen reader support ♿️ - we provide an amazing experience for english screen readers out of the box 📦. We also provide complete customisation control and internationalisation support for those who need it 💖

Conditional dragging and conditional dropping

Multiple independent lists on the one page

Flexible item sizes - the draggable items can have different heights (vertical lists) or widths (horizontal lists)

Add and remove items during a drag

Compatible with semantic <table> reordering - table pattern

Auto scrolling - automatically scroll containers and the window as required during a drag (even with keyboard 🔥)

Custom drag handles - you can drag a whole item by just a part of it

Able to move the dragging item to another element while dragging (clone, portal) - Reparenting your <Draggable />

Create scripted drag and drop experiences 🎮

Allows extensions to support for any input type you like 🕹

🌲 Tree support through the @atlaskit/tree package

A <Droppable /> list can be a scroll container (without a scrollable parent) or be the child of a scroll container (that also does not have a scrollable parent)

Independent nested lists - a list can be a child of another list, but you cannot drag items from the parent list into a child list

Server side rendering (SSR) compatible - see resetServerContext()

Plays well with nested interactive elements by default

Motivation 🤔

react-beautiful-dnd exists to create beautiful drag and drop for lists that anyone can use - even people who cannot see. For a good overview of the history and motivations of the project you can take a look at these external resources:

📖 Rethinking drag and drop

🎧 React podcast: fast, accessible and beautiful drag and drop

Not for everyone ✌️

There are a lot of libraries out there that allow for drag and drop interactions within React. Most notable of these is the amazing react-dnd. It does an incredible job at providing a great set of drag and drop primitives which work especially well with the wildly inconsistent html5 drag and drop feature. react-beautiful-dnd is a higher level abstraction specifically built for lists (vertical, horizontal, movement between lists, nested lists and so on). Within that subset of functionality react-beautiful-dnd offers a powerful, natural and beautiful drag and drop experience. However, it does not provide the breadth of functionality offered by react-dnd. So react-beautiful-dnd might not be for you depending on what your use case is.
