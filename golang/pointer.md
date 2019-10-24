# go指针型参数传递
func test(a *Test)[]*Test{<br>
	var array []*Test<br>
	b:=*a<br>
	array=append(array,b)<br>
	return array<br>
}
