# MErhaba


```csharp
class Test
{
	static void Split(string name, out string firstNames,
	out string lastName)
	{
		int i = name.LastIndexOf(' ');
		firstNames = name.Substring(0, i);
		lastName = name.Substring(i + 1);
	}
	static void Main()
	{
		string a, b;
		Split("Stevie Ray Vaughan", out a, out b);
		Console.WriteLine(a); // Stevie Ray
		Console.WriteLine(b); // Vaughan
	}
}

```
