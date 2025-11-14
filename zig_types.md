| Type         | Meaning / Example                                              |
| ------------ | -------------------------------------------------------------- |
| u8           | one u8                                                         |
| ?u8          | optional u8 (can be null or a u8 value)                        |
| *u8          | pointer to one u8                                              |
| ?*u8         | optional pointer to one u8 (can be null or a pointer)          |
| *?u8         | pointer to an optional u8 (points to a value that may be null) |
| u8           | two u8s                                                        |
| ? u8         | optional array of two u8s                                      |
| [*]u8        | pointer to unknown number of u8s                               |
| ?[*]u8       | optional pointer to unknown number of u8s                      |
| [*]const u8  | pointer to unknown number of immutable u8s                     |
| ?[*]const u8 | optional pointer to unknown number of immutable u8s            |
| * u8         | pointer to an array of 2 u8s                                   |
| ?* u8        | optional pointer to an array of 2 u8s                          |
| *const u8    | pointer to an immutable array of 2 u8s                         |
| ?*const u8   | optional pointer to an immutable array of 2 u8s                |
| []u8         | slice of u8s                                                   |
| ?[]u8        | optional slice of u8s                                          |
| []const u8   | slice of immutable u8s                                         |
| ?[]const u8  | optional slice of immutable u8s                                |
| []*u8        | slice of pointers to u8s                                       |
| ?[]*u8       | optional slice of pointers to u8s                              |
| []*const u8  | slice of pointers to immutable u8s                             |
| ?[]*const u8 | optional slice of pointers to immutable u8s                    |

  FREE ZIG POINTER CHEATSHEET! (Using u8 as the example type.)
+---------------+----------------------------------------------+
|  u8           |  one u8                                      |
|  *u8          |  pointer to one u8                           |
|  [2]u8        |  two u8s                                     |
|  [*]u8        |  pointer to unknown number of u8s            |
|  [*]const u8  |  pointer to unknown number of immutable u8s  |
|  *[2]u8       |  pointer to an array of 2 u8s                |
|  *const [2]u8 |  pointer to an immutable array of 2 u8s      |
|  []u8         |  slice of u8s                                |
|  []const u8   |  slice of immutable u8s                      |
+---------------+----------------------------------------------+
