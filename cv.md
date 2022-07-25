
# Askhat Bakitov
![Askhat Bakitov](Askhat.jpeg "Askhat Bakitov")
## Junior Frontend Developer

## Contact information:

- **Phone:** +7 702 402 52 82 
- **Email:** bakitov.askhat@gmail.com
- **Discord** darzox
- **Telegram:** @ddarzox
[Behance](https://www.behance.net/askhajan553e1c)

## About myself:

I am electrical engineer who wants to change career path. One of my main strength, that I want to point out is *perseverance*. 
As electrical engineer I have worked as electrical design engineer who designs and develop electrical systems and have worked as electrical fieldside engineer who's goal is maintain electrical systems and machines. 

Most of my jobs was shift work(rotational type), so I had time to self-study myself: HTML, CSS, Adobe Photoshop.

## Skils:

- HTML,CSS
- Basic Golang
- Photoshop
- Git,
- AutoCAD
- VS Code

## Code example:
**Instructions:** Write a function called Chunk that receives as parameters a slice, slice []int, and a number size int. The goal of this function is to chunk a slice into many sub slices where each sub slice has the length of size.

If the size is 0 it should print a newline ('\n').

```go
func Chunk(slice []int, size int) {
	singleSlice := []int{}
	doubleSlice := [][]int{}
	if size == 0 {
		fmt.Println()
		return
	}
	if len(slice) == 0 {
		fmt.Println("[]")
		return
	}
	for i, d := range slice {
		if i%size == 0 && i != 0 {
			doubleSlice = append(doubleSlice, singleSlice)
			singleSlice = []int{}
		}
		singleSlice = append(singleSlice, d)
	}
	doubleSlice = append(doubleSlice, singleSlice)
	fmt.Println(doubleSlice)
}
```

## Projects:

- [Online-shop](https://darzox.github.io/mishki--adaptive-responsive/) - HTML, CSS
- [Barbershop](https://darzox.github.io/barbershop--adaptive-responsive/) - HTML, CSS
- [Ascii representation web-app](https://github.com/darzox/ascii-art-export) - HTML, CSS, Golang


## Languages:

- English - Intermediate ([my test](http://links.t-educationfirst.mkt4686.com/servlet/MailView?ms=NTY0Mzg4NTES1&r=LTc3ODU4MDQ4MjMS1&j=MTg0MDU5MzkxNwS2&mt=1&rt=0) in EF)
- Russian - Proficient
- Kazakh - Native 