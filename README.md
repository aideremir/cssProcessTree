cssProcessTree
==============

Builds process tree. CSS only

Basing on http://thecodeplayer.com/walkthrough/css3-family-tree, but with some changes for process trees. 
To build process tree we consider that every event is the child of previous event, so if we describe linear process, we will see such markup:

<ul>
  <li><span>First event</span>
      <ul>
        <li><span>Second event</span></li>
      </ul>
  </li>
</ul>
