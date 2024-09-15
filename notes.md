# Main
### std::clog
Character log, associated with the standard C output stream stderr

Buffered standard error system used to output erros

Error messages are inserted into the buffer to be displayed later
### Stream
Abstraction that represents a device on which I/O operations are performed.

ssociated to a physical source or destination of characters; disk file, keyboard, console, etc.
        
For example, file streams are C++ objects to manipulate and interact with files.
### std::flush
Causes the stream buffer to flush its output buffer
        
For example, when stdout is flushed the characters appear in the console

### Auto keyword
Type being declared will be automatically deducted from it's initializer

Was added in C++ 11.
### Type inference
Automatic deduction of the type of an expression.

# vec3
### Const member functions
Function denied permission to change the values of the data members of the class.
### Default Arguments
Value provided in a function declaration that is automatically assigned by the compiler if the calling function doesn't provide a value as an argument.
    Point(int i = 0, int j = 0) {}
### Member Initializer List
Used in initializing the data members of a class.

    Point(int i = 0, int j = 0) : x(i), y(j) {

    }
Is the same as:

    Point(int i = 0, int j = 0) {
        x = i;
        y = j;
    }
### Inline Functions
Reduce function call overhead by expanding the function in line when it is called.

Useful for small functions when the execution time is less than the switching time.
### std::ostream
Output stream used to write sequences of characters.
std::cout and std::cerr are examples.
### alias
Used to declare a name to use as a synonym for a previously declared type.
### Two Const keywords
First const qualifies the return value as immutable.

Second const specifies the function does not modify the class instance (or any member of it).
    const vec& origin() const {
        return orig;
    }
### Ternary Operator
    condition ? expression1 : expression2;
If condition is true, expression1 is executed.

If condition is false, expression2 is executed.
### Linear Interpolation (Lerp)
Linear blend between two values.

Used to linearly scale 0.0 <= a <= 1.0:\
When a = 1.0, I want blue.\
When a = 0.0, I want white.\
In between, I want a blend.

    blendedValue = (1 - a) * startValue + a * endValue
### Aspect Ratio
 Proportional relationship between an image's width and height.\
 4:3 (Fullscreen) and 16:9 (HD Video) are common for TV.

    A 16:9 resolution is 1920x1080 (1080p)
    1920 / 16 = 120
    1080 / 9  = 120 


### Focal Length

    Smaller focal length = bigger FOV
    Bigger focal length = smaller FOV