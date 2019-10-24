# go指针型参数传递
func test(a *Test)[]*Test{
	var array []*Test
	b:=*a
	array=append(array,b)
	return array
}