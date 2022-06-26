Local libraries used by your project.

The pattern in this layout can be applied to the local libraries as well:
    - local-lib-1 and local-lib-2 can have their own 'inc' and 'src' folders.
    - the root CMakeLists.txt specifies the names for the known local libraries
    - each library manages its files and create the targets based on the names provided by the root CMakeLists.txt