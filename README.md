firepart
========

FirePart&trade; is a universal part identification system for FirePick products.

FirePart&trade; identifiers are generated from part descriptions. For example:

<pre>
{
  "01.category":"fastener",
  "02.unit":"mm",
  "03.diameter":3,
  "04.function":"screw",
  "05.length":10,
  "06.head":"socket-head-cap"
}
</pre>

The above part description uniquely corresponds to the following FirePart&trade; identifier:

`229845f397d653faf2578e532d25681623d3d0c4`

From the firepart directory, you can print out the description of a FirePart&trade identifier; as follows:

<pre>cat `git ls-tree -r HEAD | grep 229845f397d653faf2578e532d25681623d3d0c4 | sed "s/.*\s//"`</pre>


