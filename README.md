# myModule
Lesson from the book [Mastering Go - Second Edition]( https://learning.oreilly.com/library/view/mastering-go/9781838559335/ )

## Create the code
```bash
<<'eof' cat > aSourceFile.go
package main 
  
import ( 
    "fmt" 
) 
 
func main() { 
    fmt.Println("This is a sample Go program!") 
} 
eof
```

## Compile the code
```bash
go build aSourceFile.go
```

## Check the executable
```bash
file aSourceFile
```

## Run the executable
```bash
./aSourceFile
```


