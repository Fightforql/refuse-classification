在读取文件的时候使用了相对路径，因此应当把编译之后的文件夹放在源文件文件夹中，类似github中的结构组织。即：如果这个github文件被克隆到了 /dir ，那么demo的路径就是 /dir/demo ，那么编译出来的文件位置就应该在 /dir/demo/build 。这样才能保证文件可以正常被读写，否则可能出现闪退或者找不到垃圾这种情况。
demo文件夹中的release文件夹就是本地编译出来的结果，运行其中的exe就可以了。