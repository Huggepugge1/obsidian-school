# Memory
Memories are 2 dimensional arrays of cells where each cell stores one [[bit]]. When the data is read, the computer reads it as rows. The read is then sent to the end of the array to be transmitted. This means row enables (reads) is a [[1-hot]] operation.

## SLC vs MLC vs TLC vs QLC vs PLC
SLC means that ever memory cell stores one [[bit]]. In newer SSDs we can actually store more than one, in fact we can store up to 5 [[Bit|bits]] per cell using what's known as PLC. This is done by using different [[Voltage|voltages]] to represent different values. The main problem with this is [[noise]] and speed. But with a lot of error correcting the space savings still outweigh the negatives of using multiple [[Bit|bits]] per cell. Today TLC is the most common.