# Dogma
**This is an archive of coding practices & style guidelines that should be adopted by KCS members**

- [Dogma](#dogma)
	- [Generic](#generic)
		- [Generic Dogma](#generic-dogma)
		- [Generic Style](#generic-style)
	- [Contributing](#contributing)

## Generic

### Generic Dogma

Best practices to being a clean and effective software developer.

1. **Dont obfuscate** - Dont overload lines with too much logic. This makes code unclear and unreliable. Use consistent indentation and keep code simple. Dont deep nest, group code, keep naming & indentation consistent as per guidelines and commit in small blocks.
2. **Comment often** - Code makes no sense 90% of the time to everybody. Do your job as a community member. Write good comments and write them often. Good comments help everyone and helps the future of the club.
3. **Use microservice architecture** - Projects and features should be developed using a microservice architecture. This allows easier collaberation and decouples the code. This allows easier code reuse and interoperability.
4. **Review code** - Reviewing code allows you to grow as a programmer. It develops skill in reading code that isn't your own. In additon this helps the future of the club. We can catch bugs and help eachother to blossom into great software developers.
5. **Run tests!** - ALWAYS, ALWAYS run test before creating a pull request!

### Generic Style

Confrom to the [editorconfig](../.editorconfig) contained in every repository.

**Eample Code**
```cpp
// Description of why your code does what it does
class MyClass
{
public:

	MyClass(int id)
	{
		class_id = id;
	}

	int getID() { return class_id; }

private:

	int class_id;
}
```

**Outline**
- **Commenting** - 
  - Describe the purpose of your code & what it does.
  - Write proper & conforming documentation comments.
- **Naming** - 
  - Use full descriptive words with proper spelling.
  - Constatns should be in full CAPS_SNAKE_STYLE
  - Describe the purpose of your code & what it does.
  - Varibales should be camelCase
  - Classes should be full CamelCase
- **Braces** - 
  - Braces shall be places on a newline
	```cpp
	while (true)
	{
		printf("%s", "Hello World!");
	}
	```
- **Spacing** - 
  - Seperate independent tasks into new lines.
  - Seperate scopes with a blank line
  - Place spaces around boolean operators. Use brackets to group expressions.
	```cpp
	int z = sqrt((x * 2) + (y * 2));

	bool hello = true || false;
	```
- **Other** - 
  - DRY. Dont Repeat Yourself. Don't duplicate code kiddo.
  - Use consistent indentation.
  - Group similar code blocks.
  - Limit line length to 120 characters.
  - Develop iteratively, write code in small sections.


## Contributing
