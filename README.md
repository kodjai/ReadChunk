# ReadChunk
A modified PvPipelineSample which shows how to read Chunk data from an image buffer.
In this sample you can enable chunk data by setting the ChunkModeActive feature in the camera. If the payload is image type, the buffer gets checked for chunk data and if chunk data is available it prints out the count of chunks, attaches the chunks to the GenICam node map and reads ChunkWidth as an example.
