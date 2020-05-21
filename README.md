# Shared event example

Instead of creating a special thread, you can use a shared event queue, which shares the queue with other system components, saving RAM. Because the event queue is shared, you should limit the execution time of your event functions to avoid delaying other users’ events excessively. 

MIRRORED FROM MASTER EXAMPLE SNIPPETS REPOSITORY: mbed-os-examples-docs_only.
ANY CHANGES MADE DIRECTLY TO THIS REPOSITORY WILL BE AUTOMATICALLY OVERWRITTEN.
