This repository demonstrates a potential issue with unexpected iteration order when using Lua's `pairs` iterator on nested tables.  The `bug.lua` file contains code that recursively iterates through a nested table.  While seemingly simple, the output can be unpredictable due to the unordered nature of `pairs`. The `bugSolution.lua` file provides a possible solution to address this issue by using a different approach that guarantees iteration order.