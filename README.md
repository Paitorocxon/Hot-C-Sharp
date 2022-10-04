# Hot-C-Sharp
Ad-Hoc Runtime Compiling Service for quick Batch-like Coding.
Create files with C#-Code an execute them by double-clicking the source file.

The Purpose of this tool is to deliver a fast solution for quick and small application which are to complex to be a batch-script.
That's it!

Download, associate the file exgtension .hcs to the HCS "Tunneler" and you should be able to run it all over your system (as long as your systems security policy allows it)

You can use 
{{
System.Console.WriteLine("Hello World");
}}


instead of
namespace bla {
public static void Main(string[]args) {
System.Console.WriteLine("Hello World");
}}
For CSC see https://github.com/dotnet/roslyn/tree/main/src/Compilers/CSharp/csc
