<div align="center">
	<img src="banner.png" alt="Logo" width="260" height="128">
	<h1 align="center">iOS Interview Questions</h1>
	<p align="center">A compilation of 151 commonly asked <a href="https://www.hackingwithswift.com/interview-questions" target="_blank">interview questions</a> for iOS developers with their respective answer.</p>
	<p>
		<a href="https://github.com/HenestrosaDev/ios-interview-questions/stargazers">
			<img alt="GitHub Contributors" src="https://img.shields.io/github/stars/HenestrosaDev/ios-interview-questions" />
		</a>
		<a href="https://github.com/HenestrosaDev/ios-interview-questions/graphs/contributors">
			<img alt="GitHub Contributors" src="https://img.shields.io/github/contributors/HenestrosaDev/ios-interview-questions" />
		</a>
		<a href="https://github.com/HenestrosaDev/ios-interview-questions/issues">
			<img alt="Issues" src="https://img.shields.io/github/issues/HenestrosaDev/ios-interview-questions" />
		</a>
		<a href="https://github.com/HenestrosaDev/ios-interview-questions/pulls">
			<img alt="GitHub pull requests" src="https://img.shields.io/github/issues-pr/HenestrosaDev/ios-interview-questions" />
		</a>
		<a href="https://github.com/HenestrosaDev/ios-interview-questions/blob/main/LICENSE">
			<img alt="GitHub pull requests" src="https://img.shields.io/github/license/HenestrosaDev/ios-interview-questions" />
		</a>
	</p>
	<p>
		<a href="https://github.com/HenestrosaDev/ios-interview-questions/issues/new/choose">Report Issue</a> · <a href="https://github.com/HenestrosaDev/ios-interview-questions/discussions">Ask Question</a>
	</p>
</div> 

## Table of Contents

- [Before You Start](#before-you-start)
- Question Categories
	- [Accessibility](#accessibility)
	- [Data](#data)
	- [Design Patterns](#design-patterns)
	- [Frameworks](#frameworks)
	- [iOS](#ios)
	- [Miscellaneous](#miscellaneous)
	- [Performance](#performance)
	- [Security](#security)
	- [Swift](#swift)
	- [SwiftUI](#swiftui)
	- [UIKit](#uikit)
- [License](#license)
- [Authors](#authors)
- [Support](#support)

## Before You Start

- Questions taken from [hackingwithswift.com](https://www.hackingwithswift.com/interview-questions) and answered by me with the help of [Swift Book](https://docs.swift.org/swift-book/documentation/the-swift-programming-language/), [Hacking with Swift](https://www.hackingwithswift.com/), [StackOverflow](https://www.stackoverflow.com/) and [ChatGPT](https://chat.openai.com/).

- These colors indicate the difficulty level of the questions:
	- 🟩 Beginner question
	- 🟧 Intermediate question
	- 🟥 Advanced question

- I've made a blog post with all the contents of this file on [my website](https://henestrosa.dev/blog/151-ios-interview-questions/).

---

## Accessibility

- 🟩 [How much experience do you have testing with VoiceOver?](https://www.hackingwithswift.com/interview-questions/how-much-experience-do-you-have-testing-with-voiceover)
	<details>
		<summary>Answer</summary>
	
	The answer depends on your experience with VoiceOver. Here's how I would approach it:
 
	>I would say that I have a fair amount of experience testing with VoiceOver. It is an essential part of making sure that an iOS app is accessible to all users, including those who are visually impaired. To test with VoiceOver, the developer can enable VoiceOver on their test device and navigate through the app using only VoiceOver. This involves listening to the VoiceOver descriptions of each element on the screen and verifying that they are accurate and meaningful.
	>
	>For example, when testing a button, the developer would want to ensure that VoiceOver correctly reads out the label of the button and provides any necessary contextual information. They would also want to verify that the button is in the correct order in the navigation flow and that it can be activated using only voice commands.
	>
	>Testing with VoiceOver can be time-consuming, but it is an essential step in creating an accessible app. By testing with VoiceOver, developers can ensure that their app is easy to use for all users, regardless of their visual abilities.
	</details>

- 🟩 [How would you explain Dynamic Type to a new iOS developer?](https://www.hackingwithswift.com/interview-questions/how-would-you-explain-dynamic-type-to-a-new-ios-developer)
	<details>
		<summary>Answer</summary>
	
	Dynamic Type is a feature in iOS that allows users to adjust the font size of text displayed in apps. It gives users the ability to increase or decrease the size of the text to make it easier to read, and it also helps to ensure that text is legible for people with visual impairments.

	We can use Dynamic Type to make an app more accessible and user-friendly. Instead of specifying a fixed font size for the text, we can use Dynamic Type to allow the user's preferred text size to be applied throughout an app. We can do this by using font size constants that are tied to the user's preferred text size setting, such as `UIFontTextStyleBody` or `UIFontTextStyleHeadline`.
	</details>

- 🟩 [What are the main problems we need to solve when making accessible apps?](https://www.hackingwithswift.com/interview-questions/what-are-the-main-problems-we-need-to-solve-when-making-accessible-apps)
	<details>
		<summary>Answer</summary>

	When making accessible apps, the main problems we need to solve are:

	- **Providing sufficient visual and auditory cues**: This includes ensuring that visual elements such as text, buttons, and icons are clear and easy to read, and that auditory elements such as sound effects and voiceovers are clear and easily distinguishable.
	- **Supporting assistive technologies**: This involves ensuring that our app is compatible with screen readers, such as VoiceOver, and other assistive technologies that people with disabilities may rely on to interact with their devices.
	- **Providing alternative input methods**: Some people may not be able to use a touchscreen, so it's important to provide alternative input methods such as voice commands or keyboard navigation.
	- **Ensuring that our app is keyboard accessible**: This means that all functionality within our app can be accessed using only the keyboard.
	- **Providing sufficient color contrast**: People with visual impairments may have difficulty distinguishing between certain colors, so it's important to ensure that our app provides sufficient color contrast for all text and visual elements.
	- **Making sure that our app is usable for everyone**: Accessibility is not just about accommodating people with disabilities, but also about ensuring that our app is usable for everyone, regardless of their abilities or limitations. This means designing our app with clear and intuitive navigation, simple and easy-to-use interfaces, and avoiding the use of complex or confusing gestures.
	</details>

- 🟧 [What accommodations have you added to apps to make them more accessible?](https://www.hackingwithswift.com/interview-questions/what-accommodations-have-you-added-to-apps-to-make-them-more-accessible)
	<details>
		<summary>Answer</summary>

	The answer depends on your experience with adding accommodations to make apps more accessible. Here's how I would approach it:
	
	>- **Implementing Dynamic Type**: This allows users to adjust the font size in the app to better suit their needs.
	>- **Providing alternative text for images**: This allows users with visual impairments to understand the content of the app.
	>- **Using VoiceOver**: This allows users to interact with the app using spoken feedback and gestures.
	>- **Adding closed captions**: This allows users with hearing impairments to understand the audio content in the app.
	>- **Making sure the app is navigable with a keyboard**: This allows users with motor impairments to use the app without a touchscreen.
	>- **Ensuring good color contrast**: This allows users with visual impairments to distinguish between different elements in the app.
	</details>

<p align="right">(<a href="#top">back to top</a>)</p>

## Data

- 🟩 [How is a dictionary different from an array?](https://www.hackingwithswift.com/interview-questions/how-is-a-dictionary-different-from-an-array)
	<details>
		<summary>Answer</summary>
	
	In Swift, an array is an ordered collection of values of the same type, while a dictionary is an unordered collection of key-value pairs.

	In an array, each element is accessed by its index, which is an integer starting from zero. The order of the elements in the array is determined by their position in the array.

	In a dictionary, each value is associated with a unique key, which can be of any hashable type, such as a string or an integer. Keys are used to look up values in the dictionary, rather than indices. Unlike arrays, the order of the elements in a dictionary is not guaranteed.
	</details> 

- 🟩 [What are the main differences between classes and structs in Swift?](https://www.hackingwithswift.com/interview-questions/what-are-the-main-differences-between-classes-and-structs-in-swift)
	<details>
		<summary>Answer</summary>

	In Swift, both classes and structs are used to define custom data types. While they share many similarities, there are some key differences between them:

	- **Inheritance**: A class can inherit from another class, but a struct cannot. This means that classes can build on the functionality of other classes, while structs are limited to their own implementation.
	- **Reference vs Value Types**: When we pass a class instance to a function or assign it to a new variable, we're creating a reference to that instance. This means that any changes made to the instance will be reflected across all references to it. On the other hand, when we pass a struct instance or assign it to a new variable, we're creating a copy of that instance. Any changes made to the copy will not affect the original instance. This can make structs more predictable and less prone to bugs, but also less flexible. **Note that a struct instance can be modified when passed to a function if the parameter is defined with the `inout` keyword, meaning that it can be modified inside the function, and those modifications will be reflected in the original value outside the function**.
	- **Mutability**: In general, classes are more flexible and mutable than structs. We can add and remove properties and methods from a class at runtime, while a struct's properties and methods are fixed at compile time.
	- **Initialization**: Structs have member-wise initializers automatically generated for them by default, while classes do not. This means that when we create a new instance of a struct, we can pass in all of its properties as arguments to the initializer. With classes, we need to define our own initializer(s) to achieve the same effect.
	- **Memory management**: Classes are managed by reference counting, meaning that instances are deallocated when their reference count drops to zero. Structs, on the other hand, are copied by value, and their lifetimes are determined by the scope in which they're defined.
	<br />

	In general, we should choose classes when we need the features they provide, such as inheritance or reference types, and choose structs when we want to take advantage of their predictability, immutability, and value semantics.
	</details> 

- 🟩 [What are tuples and why are they useful?](https://www.hackingwithswift.com/interview-questions/what-are-tuples-and-why-are-they-useful)
	<details>
		<summary>Answer</summary>

	In Swift, tuples are a lightweight way to group multiple values into a single compound value. A tuple can contain two or more values of any type, including other tuples. They are useful when we want to pass around a single value that consists of multiple values, and creating a separate custom data structure would be overkill. In a sense, they are like anonymous structs.

	One of the primary benefits of tuples is that they allow us to group together a small number of related values in a concise and expressive way. For example, we could use a tuple to represent a point in two-dimensional space with an x-coordinate and y-coordinate. Instead of defining a custom class or struct to hold these two values, we can use a tuple with two elements, like this:

	```swift
	let point = (x: 10, y: 20)
	```
	
	Another use case for tuples is when we want to return multiple values from a function, but we don't want to define a custom data structure to hold those values. Tuples provide a lightweight and easy way to return multiple values as a single compound value. For example:

	```swift
	func calculateMinMax(numbers: [Int]) -> (min: Int, max: Int)? {
		guard let first = numbers.first else {
			return nil
		}

		var min = first
		var max = first

		for number in numbers {
			if number < min {
				min = number
			} else if number > max {
				max = number
			}
		}
		return (min, max)
	}
	```
	
	In this example, the `calculateMinMax` function returns a tuple with two values: the minimum and maximum values in an array of integers. The tuple is marked as optional, in case the input array is empty.
	</details>

- 🟩 [What does the `Codable` protocol do?](https://www.hackingwithswift.com/interview-questions/what-does-the-codable-protocol-do)
	<details>
		<summary>Answer</summary>

	The `Codable` protocol is is a type-safe way to encode and decode data to and from different formats, such as JSON or property list (plist). It is a type alias that combines the `Encodable` and `Decodable` protocols.

	By conforming to the `Codable` protocol, a Swift type can be encoded to a binary or textual format that can be sent over a network or saved to disk, and then decoded back into a Swift object. This makes it easy to work with data from external sources such as web APIs, databases, and file systems.

	This protocol also eliminates the need to write custom serialization and deserialization code, although it's still an option if needed. Such tasks can be time-consuming and error-prone. Instead, the Swift compiler automatically generates the necessary code based on the structure of the type being encoded or decoded.
	</details>

- 🟩 [What is the difference between an array and a set?](https://www.hackingwithswift.com/interview-questions/what-is-the-difference-between-an-array-and-a-set)
	<details>
		<summary>Answer</summary>

	In Swift, an array is an ordered collection of values of the same type, whereas a set is an unordered collection of unique values of the same type.

	Here are some key differences:

	- **Order**: Arrays have a specific order, and the elements in an array are accessed using their index, whereas sets are unordered, and the elements in a set are accessed using their value.
	- **Duplicates**: Arrays can contain duplicate values, whereas sets only contain unique values.
	- **Performance**: Sets are optimized for fast membership testing, which means that they are typically faster than arrays when checking whether an element exists in the collection. However, sets are typically slower than arrays when accessing elements by index.
	<br />

	We can convert an array to a set and vice versa. However, when we convert an array to a set, we have to keep in mind that we lose both the order of the elements and the duplicate elements. Also, if we want to store custom data types in a set, we need to make sure that it conforms to the `Hashable` protocol, which ensures a consistent way of generating hash values and checking for equality, so that duplicate objects aren't accidentally added.
	</details>

- 🟩 [What is the difference between the `Float`, `Double`, and `CGFloat` data types?](https://www.hackingwithswift.com/interview-questions/what-is-the-difference-between-the-float-double-and-cgfloat-data-types)
	<details>
		<summary>Answer</summary>
	
	In Swift, `Float` and `Double` are floating-point data types used to represent decimal values with a limited and extended precision, respectively. The `CGFloat` data type is used in UIKit and Core Graphics frameworks, and it represents a floating-point value with a precision equivalent to the platform's native `Float` type on 32-bit platforms and `Double` type on 64-bit platforms.

	The main difference between `Float` and `Double` is their precision. Float has a precision of 32-bit, while `Double` has a precision of 64-bit. This means that `Double` can represent larger and more precise values than `Float`.

	On the other hand, `CGFloat` is a type alias defined by Apple that can represent floating-point values with the same precision as the platform's native `Float` or `Double` type. `CGFloat` is often used in Core Graphics and UIKit frameworks for graphics-related calculations and drawing operations.
	</details>

- 🟩 [What's the importance of key decoding strategies when using `Codable`?](https://www.hackingwithswift.com/interview-questions/whats-the-importance-of-key-decoding-strategies-when-using-codable)
	<details>
		<summary>Answer</summary>

	They are essential because they allow us to map the keys of our JSON (or other data formats) to the Swift properties of our structs or classes. This is crucial because the keys of our JSON may not match the property names we want to use in our Swift code.

	There are several key decoding strategies available in Swift, including:

	- `useDefaultKeys`: This strategy uses the property names as the keys in the JSON.
	- `convertFromSnakeCase`: This strategy converts keys in the JSON from snake_case to camelCase.
	- `custom`: This strategy allows us to define our own key mapping using a closure.
	<br />

	Using the correct key decoding strategy is important because it ensures that our data is decoded correctly into our Swift objects, which can help prevent bugs and ensure that our app works as expected.
	</details>

- 🟩 [When using arrays, what's the difference between `map()` and `compactMap()`?](https://www.hackingwithswift.com/interview-questions/when-using-arrays-whats-the-difference-between-map-and-compactmap)
	<details>
		<summary>Answer</summary>

	Both `map()` and `compactMap()` are higher-order functions available for types that conform to the `Sequence` protocol in Swift (e.g., arrays and sets). Both take a closure as an argument and apply the closure to each element of the array. However, the `map()` function returns an array with the transformed elements, while `compactMap()` returns an array with the non-nil transformed elements. Therefore, `compactMap()` is useful when we want to transform elements of an array that may have `nil` values and remove them from the result.

	Here's an example:

	```swift
	let numbers = ["1", "2", "3", "four", "5"]

	// Using map() to convert the string numbers to integers
	let mapped = numbers.map { Int($0) } // [1, 2, 3, nil, 5]

	// Using compactMap() to convert the string numbers to integers and remove the nil value
	let compactMapped = numbers.compactMap { Int($0) } // [1, 2, 3, 5]
	```
	
	In the example above, the `map()` function is used to convert each string element of the `numbers` array to an integer. However, since `"four"` cannot be converted to an integer, it is returned as `nil`. The resulting array from `map()` contains `nil` for the `"four"`, so its type is `[Int?]`. On the other hand, `compactMap()` is used to convert each string element to an integer and remove the `nil` values. The resulting array from `compactMap()` only contains integers, so its type is `[Int]`.
	</details>

- 🟩 [Why is immutability important?](https://www.hackingwithswift.com/interview-questions/why-is-immutability-important)
	<details>
		<summary>Answer</summary>

	Immutability is important for the following reasons:

	- **Avoiding unintended changes**: When a variable or object is mutable, it can be changed at any time, leading to unintended changes that can cause bugs and errors. By making variables and objects immutable, we can avoid such unintended changes.
	- **Thread safety**: Immutable objects are inherently thread-safe, as they cannot be changed by multiple threads simultaneously. This can make concurrent programming much easier and less error-prone.
	- **Clarity and simplicity**: When objects are immutable, it is clear that their state cannot change, which can make code easier to reason about and understand. Immutability can also simplify certain algorithms and data structures, such as functional programming techniques.
	- **Performance**: In some cases, immutable data structures can be more performant than mutable ones. This is because they do not need to perform additional checks and operations to ensure their state is consistent.
	<br />
	</details> 

- 🟧 [What are one-sided ranges and when would you use them?](https://www.hackingwithswift.com/interview-questions/what-are-one-sided-ranges-and-when-would-you-use-them)
	<details>
		<summary>Answer</summary>
	
	One-sided ranges are a feature introduced in Swift 4 that allow us to create a range that includes all elements from a starting index or up to an ending index. I would use them to perform operations on collections, such as slicing arrays, iterating over subsets, or working with substrings, without having to explicitly define both endpoints.

	The syntax for a one-sided range is either `..<`, `start...`, or `...end`. The `..<` operator creates a range that **does not include** the value of the right operand, while the `...` operator creates a range that **includes** the value of the right/left operand.

	For example, if we have an array `numbers` with 5 elements, we can use a one-sided range to access a subset of the elements:

	```swift
	let numbers = [1, 2, 3, 4, 5]

	// access elements from index 2 to the end
	let subset1 = numbers[2...]
	// subset1 is [3, 4, 5]

	// access elements up to index 3
	let subset2 = numbers[..<3]
	// subset2 is [1, 2, 3]
	```
 	</details> 

- 🟧 [What does it mean when we say “strings are collections in Swift”?](https://www.hackingwithswift.com/interview-questions/what-does-it-mean-when-we-say-strings-are-collections-in-swift)
	<details>
		<summary>Answer</summary>

	In Swift, a `String` is a collection type, which means that it can be treated as a sequence of individual elements, or characters, that can be iterated over using various methods, such as loops and higher-order functions like `map`, `filter`, and `reduce`. This is because, under the hood, a `String` is represented by a collection of `Character` values, each of which represents a single Unicode character.

	As a collection, a `String` has several useful properties and methods inherited from the `Collection` protocol, including `count`, `isEmpty`, and `first`, as well as subscripting using integer indices or ranges. Additionally, `String` also provides many specific methods for working with strings, such as `hasPrefix`, `hasSuffix`, and `replacingOccurrences`, which makes it easier to manipulate and transform string values in various ways.
	</details> 

- 🟧 [What is a `UUID`, and when might you use it?](https://www.hackingwithswift.com/interview-questions/what-is-a-uuid-and-when-might-you-use-it)
	<details>
		<summary>Answer</summary>

	`UUID` stands for Universally Unique Identifier. It is a 128-bit value that is used to identify _almost unique_ objects, resources, or entities in a system or application where uniqueness is important, such as distributed systems, databases, or file systems.

	They are _almost unique_ because there exists a probability of generating two identical UUIDs, although it's extremely small and depends on the number of entities created and the speed at which we create them.

	In Swift, the `UUID` class is used to generate UUIDs. We can use UUIDs in a variety of situations where we need a unique identifier, such as:

	- To identify objects or resources in a distributed system where multiple nodes need to access the same resource.
	- To create unique identifiers for user accounts or other entities in a database.
	- To generate unique filenames or file IDs in a file system.
	- To track application usage or events in analytics.
	- To prevent collisions when generating random numbers.
	</details> 

- 🟧 [What's the difference between a value type and a reference type?](https://www.hackingwithswift.com/interview-questions/whats-the-difference-between-a-value-type-and-a-reference-type)
	<details>
		<summary>Answer</summary>

	In Swift, value types and reference types are two fundamental ways in which data is managed in memory. They differ in how they handle assignment, copying, and reference sharing.

	A **value type** creates a new copy of its data when it is assigned to a variable, or passed to a function. Changes to one instance of a value type do not affect other instances.

	Value types in Swift include basic data types like `Int`, `Double`, `Bool`, and `String`, as well as more complex types such as structs and enums.

	Here's an example:

	```swift
	struct Point {
		var x: Int
		var y: Int
	}
	
	var point1 = Point(x: 1, y: 2)
	var point2 = point1  // Creates a copy of `point1`
	point2.x = 10        // Modifying `point2` does not affect `point1`
	
	print(point1.x)  // Output: 1
	print(point2.x)  // Output: 10
 	```

	However, value types can be modified from a function if the parameter is defined with the `inout` keyword. Those modifications will be reflected in the original value outside the function. For example, if you want to double a number in place—i.e., change the value directly rather than returning a new one—you might write a function like this:

  	```swift
	func doubleInPlace(number: inout Int) {
		number *= 2
	}
   	```

   	To use it, you first need to make a variable integer—you can't use constant integers with `inout`, because they might get changed. You also need to pass the parameter to `doubleInPlace` using an ampersand, `&`, before its name, which is an explicit recognition that you know it's being used as `inout`.

  	```swift
	var myNum = 10 
	doubleInPlace(number: &myNum)
   	```

	On the other hand, a **reference type** include classes, functions, and closures. It doesn't create a copy when assigned to a new variable or passed to a function. Instead, it creates a new reference (or pointer) to the same instance in memory. Changes to one reference affect all references.

	```swift
	class Point {
		var x: Int
		var y: Int
		
		init(x: Int, y: Int) {
			self.x = x
			self.y = y
		}
	}
	
	var point1 = Point(x: 1, y: 2)
	var point2 = point1  // Both `point1` and `point2` reference the same instance
	point2.x = 10        // Modifying `point2` also affects `point1`
	
	print(point1.x)  // Output: 10
	print(point2.x)  // Output: 10
 	```
	</details> 

- 🟧 [When would you use Swift's `Result` type?](https://www.hackingwithswift.com/interview-questions/when-would-you-use-swifts-result-type)
	<details>
		<summary>Answer</summary>

	Swift's `Result` type is a generic enumeration that represents the success or failure of an operation. It is commonly used for handling asynchronous tasks or error-prone operations in a concise, expressive, and type-safe way.

	For example, we might use `Result` when making a network request. The successful result would be the data received from the network request, while the failure result would be an error that occurred during the request (e.g. a timeout, network error, or invalid response).

	Here's an example:

	```swift
	enum NetworkError: Error {
		case badURL
		case requestFailed
		case unknown
	}

 	// Network request
	func fetchData(from url: String, completion: (Result<Data, NetworkError>) -> Void) {
		guard let url = URL(string: url) else {
			completion(.failure(.badURL))
			return
		}
		
		URLSession.shared.dataTask(with: url) { data, response, error in
			if let _ = error {
				completion(.failure(.requestFailed))
			} else if let data = data {
				completion(.success(data))
			} else {
				completion(.failure(.unknown))
			}
		}.resume()
	}
	
	// Usage
	fetchData(from: "https://example.com") { result in
		switch result {
		case .success(let data):
			print("Data received: \(data)")
		case .failure(let error):
			print("Error occurred: \(error)")
		}
	}
 	```
	</details> 

- 🟥 [What is type erasure and when would you use it?](https://www.hackingwithswift.com/interview-questions/what-is-type-erasure-and-when-would-you-use-it)
	<details>
		<summary>Answer</summary>

	Type erasure is a technique in Swift that allows us to work with values of generic or protocol-constrained types in a way that hides their specific underlying type, making it possible to use a uniform interface while still maintaining type safety. 

	It is often used to:

	- Work with heterogeneous collections or APIs that require a single type.
	- Pass around protocol-constrained types without exposing the concrete type.
	- Abstract over generic or protocol requirements, especially with protocols that include associated types or self-requirements.
	<br>

	Type erasure is necessary because some protocols in Swift cannot be used directly as a concrete type because they either have:

	- **Associated types**, such as `Collection` or `Equatable`, which depend on generic parameters, making them inherently incomplete without a specific type.
 	- References to `Self`, which cannot be used as a type for variables or collections.
	<br>

 	The following example reflects the previous explanation:
  
	```swift
	protocol Shape {
		func area() -> Double
	}
	
	struct Circle: Shape {
		let radius: Double
		func area() -> Double { return .pi * radius * radius }
	}
	
	struct Square: Shape {
		let side: Double
		func area() -> Double { return side * side }
	}
	
	// You can't do this:
	let shapes: [Shape] = [Circle(radius: 5), Square(side: 10)]
	// Error: Protocol 'Shape' can only be used as a generic constraint because it has Self or associated type requirements.
 	```

	Type erasure solves this problem by wrapping protocol-conforming objects in a type that hides the underlying type. Following the previous example, we would do the following to apply it:

	```swift
	protocol Shape {
		func area() -> Double
	}
	
	struct Circle: Shape {
		let radius: Double
		func area() -> Double { return .pi * radius * radius }
	}
	
	struct Square: Shape {
		let side: Double
		func area() -> Double { return side * side }
	}
	
	// Type erasure wrapper
	struct AnyShape: Shape {
		private let _area: () -> Double
		
		init<S: Shape>(_ shape: S) {
			_area = shape.area
		}
		
		func area() -> Double {
			return _area()
		}
	}
	
	// Using the wrapper
	let shapes: [AnyShape] = [AnyShape(Circle(radius: 5)), AnyShape(Square(side: 10))]
	
	for shape in shapes {
		print("Area: \(shape.area())")
	}
 	```

	However, for common cases, Swift provides built-in type erasers, such as `AnyCollection` (type-erased wrapper for collections), and `AnyPublisher` (type-erased wrapper for publishers, part of the Combine framework).
	</details> 

<p align="right">(<a href="#top">back to top</a>)</p>

## Design Patterns

- 🟩 [How would you explain delegates to a new Swift developer?](https://www.hackingwithswift.com/interview-questions/how-would-you-explain-delegates-to-a-new-swift-developer)
	<details>
		<summary>Answer</summary>

	Delegates in Swift are a design pattern used to establish communication between objects. They work by allowing one object (the delegate) to delegate some of its responsibilities to another object, which acts as the delegate.
 
	To implement delegates in Swift, we typically define a protocol with one or more methods that the delegate can implement. The delegating object then has a delegate property that conforms to the protocol. When the delegating object wants to communicate with its delegate, it simply calls the appropriate method on the delegate.

	An example of where delegates might be used is in a table view. The table view might delegate responsibility for providing the content of each cell to another object (the data source), and responsibility for responding to user interactions with the cells to yet another object (the delegate).

	In this way, the table view can remain focused on managing the display of the cells, while delegating other responsibilities to separate objects that are better suited to handle them.
	</details>

- 🟧 [Can you explain MVC, and how it's used on Apple's platforms?](https://www.hackingwithswift.com/interview-questions/can-you-explain-mvc-and-how-its-used-on-apples-platforms)
	<details>
		<summary>Answer</summary>

	MVC stands for Model-View-Controller, which is a common design pattern used in software development. It's used to separate the concerns of each component so that changes to one don't affect the others. For example, if we need to update the **Model**, we can do so without changing the **View** or the **Controller**. This makes it easier to maintain and modify our code over time.

	Here's a brief overview of each component:

	- **Model**:
 		- Data layer of the application that contains the business logic.
 		- Contains the data and the logic for manipulating that data, including notifying the controller when data changes.
 		- In an iOS app, the **Model** might represent the data that is stored in a database or fetched from a web service.
	- **View**:
 		- Presentation layer of the application.
 		- Contains the user interface elements that the user interacts with.
 		- Views might include things like buttons, labels, text fields, and images.
		- In an iOS app, they can be created using UIKIt (programatically or with the Interface Builder) or SwiftUI.
	- **Controller**:
 		- Acts as the glue that connects the **Model** and the **View**.
 		- Handles user input and updates the **Model** and **View** accordingly.
 		- In an iOS app using UIKit, controllers are usually `UIViewControllers`, which handle user input and update the model and other views accordingly.
	<br />

	This is how the three components interact:

	1. The user interacts with the **View** (e.g., taps a button).
 	2. The **Controller** processes the input and updates the **Model**.
	3. The **Model** updates its data and notifies the **Controller**.
	4. The **Controller** updates the View to reflect changes in the **Model**.
 	<br />

  	In UIKit, this pattern often ends up with too much responsibility, leading to the infamous "Massive View Controller" problem. This can be mitigated by using additional patterns such as delegation, observers, or dependency injection to offload some responsibility. In addition, the **Controller** is tightly coupled to the **View**, making it less flexible than more modern patterns like MVVM.
  	</details>

- 🟧 [Can you explain MVVM, and how it might be used on Apple's platforms?](https://www.hackingwithswift.com/interview-questions/can-you-explain-mvvm-and-how-it-might-be-used-on-apples-platforms)
	<details>
		<summary>Answer</summary>

	MVVM stands for Model-View-ViewModel, and it is an architecture pattern that is commonly used in developing software for Apple's platforms to improve the separation of concerns and make code more testable and maintainable. It builds on the principles of MVC, but provides a better way to manage data binding and logic, especially when dealing with complex UIs.

	Here's a brief overview of each component:

	- **Model** (the same as in MVC):
		- Data layer of the application that contains the business logic.
 		- Contains the data and the logic for manipulating that data, including notifying the controller when data changes.
 		- In an iOS app, the model might represent the data that is stored in a database or fetched from a web service.
 	- **View**:
 		- Represents the UI of an app, displaying data to the user.
 		- Views might include things like buttons, labels, text fields, and images.
		- Binds to the **ViewModel** to automatically reflect changed in the data.
		- In an iOS app, they can be created using UIKIt (programatically or with the Interface Builder) or SwiftUI.
 	- **ViewModel**:
   		- Acts as the glue that connects the **Model** and the **View**.
 		- Contains presentation logic; transforms raw data from the **Model** into a form suitable for display in the **View**.
   		- Keeps the **View** updated when the **Model** changes, often using data binding.
 		- Should be independent of the UI framework, making it testable and reusable.
   		- Helps reduce "Massive View Controller" problems, as seen in the MVC pattern.
	<br />  

	This is how the three components interact:

	1. The user interacts with the **View** (e.g., taps a button).
	2. The **View** notifies the **ViewModel** of the user's action.
	3. The **ViewModel** processes the input and updates the **Model**.
	4. The **Model** updates its data.
 	5. The **ViewModel** observes changes in the **Model** and updates its own state.
  	6. The **View** observes the **ViewModel** and updates automatically to reflect the changes.
 	<br />  

	This interaction differs from MVC in that:

	- The **ViewModel** handles both user input and interaction with the **Model** (there's no **Controller** in MVVM).
	- The **View** is bound to the **ViewModel**, so it automatically updates itself when the **ViewModel** changes via data binding.
 	<br />  

	MVVM naturally fits into SwiftUI because of its declarative and reactive nature, as `ObservableObject`, `@State` and `@Published` make it easy to bind the **View** and the **ViewModel**. Although UIKit doesn't have built-in data binding like SwiftUI, you can still use delegates, closure callbacks, or Combine to connect the **View** and **ViewModel**. However, it might add extra layers of complexity to small projects.
	</details>

- 🟧 [How would you explain dependency injection to a junior developer?](https://www.hackingwithswift.com/interview-questions/how-would-you-explain-dependency-injection-to-a-junior-developer)
	<details>
		<summary>Answer</summary>

	Dependency injection is a design pattern that is used to make code more flexible, reusable, and testable. In this pattern, instead of creating objects or dependencies within a class or function, we pass them in as parameters from the outside. This helps to reduce the coupling between components and makes it easier to change or update parts of our code without having to make changes to many different places.

	In simpler terms: Instead of a class building what it needs, it gets given what it needs.

	A dependency is just something that a class relies on to do its work. For example:

	- A restaurant (class) needs ingredients (dependencies) to cook food.
	- **Without DI**: The restaurant has its own farm, fishing boat, and supply chain to get ingredients (tightly coupled).
	- **With DI**: The ingredients are delivered by a supplier (loose coupling). If the supplier changes, the restaurant can still function without altering how it cooks.
   	<br>

	If a class creates its own dependencies, it becomes tightly coupled to them, meaning:

	- We can't easily replace the dependency (e.g., for testing or updates).
	- The class becomes harder to understand and maintain.
 	<br>

	For example:

	```swift
	class Restaurant {
		let supplier = IngredientSupplier() // Restaurant is its own IngredientSupplier
		
		func prepareMeal() {
			let ingredients = supplier.deliverIngredients()
			print("Meal prepared with \(ingredients)")
		}
	}
 	```

	Here:

	- The `Restaurant` is tightly coupled to the `IngredientSupplier` class.
	- We'd have to rewrite the restaurant's operations if the restaurant stopped supplying the ingredients.
 	<br>

  	To solve these issues, we can use dependency injection to pass the dependency (an ingredient supplier) into the class, so the class doesn't create it itself. In the context of the example, imagine that the restaurant now relies on an external ingredient supplier:

  	```swift
	class Restaurant {
		let supplier: IngredientSupplier // Dependency is injected
		
		init(supplier: IngredientSupplier) {
			self.supplier = supplier
		}
		
		func prepareMeal() {
			let ingredients = supplier.deliverIngredients()
			print("Meal prepared with \(ingredients)")
		}
	}
   	```

   	Now:

  	- The restaurant does't care how the ingredients are sourced.
  	- We can easily swap suppliers without changing the code of the `Restaurant` class.
	<br>

 	On a separate note, there are three types of dependency injection:

  	- **Constructor injection**: Dependencies are passed into the class when it's created.

 		```swift
		class Restaurant {
			let supplier: IngredientSupplier
			
			init(supplier: IngredientSupplier) {
				self.supplier = supplier
			}
		}
  		```

  	- **Property injection**: Dependencies are assigned to properties after the object is created.

		```swift
		class Restaurant {
			var supplier: IngredientSupplier?
		
			func prepareMeal() {
				let ingredients = supplier.deliverIngredients()
				print("Meal prepared with \(ingredients)")
			}
		}
  		```

  	- **Method injection**:

		```swift
		class Restaurant {
			func prepareMeal() {
				let ingredients = supplier.deliverIngredients()
				print("Meal prepared with \(ingredients)")
			}
		}
  		```
	</details>

- 🟧 [How would you explain protocol-oriented programming to a new Swift developer?](https://www.hackingwithswift.com/interview-questions/how-would-you-explain-protocol-oriented-programming-to-a-new-swift-developer)
	<details>
		<summary>Answer</summary>

	Protocol-Oriented Programming (POP) is a programming paradigm that emphasizes the use of protocols (interfaces) to define behaviors, rather than relying solely on inheritance from base classes. It's about composing functionality through protocols instead of creating deep class hierarchies.

	Swift is designed with protocol-oriented programming in mind and encourages this approach as an alternative to object-oriented programming (OOP).

	A **protocol** is like a "contract" or "blueprint" that defines a set of methods, properties, or requirements. Any type (class, struct, or enum) that adopts a protocol agrees to implement those requirements.

	For example:

	```swift
	protocol Drivable {
		func start()
		func drive()
	}
	```

	Here, the `Drivable` protocol defines the "contract" that anything that is `Drivable` must have `start()` and `drive()` methods.

	In object-oriented programming, we often use inheritance to share behavior:

	```swift
	class Vehicle {
		func start() {
			print("Starting vehicle")
		}
	}
	
	class Car: Vehicle {
		func drive() {
			print("Driving car")
		}
	}
	```

	This works, but:

	- We can only inherit from one class (single inheritance).
	- If unrelated types need similar behavior, we either:
		- Create artificial parent-child relationships, which may not make sense.
		- Duplicate code across multiple classes.
	<br />
 
	Instead of relying on inheritance, POP allows us to use protocols to share behavior across any type (class, struct, or enum). This avoids the limitations of single inheritance and makes code more modular and reusable.

	```swift
	protocol Drivable {
		func start()
		func drive()
	}
	
	struct Car: Drivable {
		func start() {
			print("Starting car")
		}
	
		func drive() {
			print("Driving car")
		}
	}
	
	struct Bicycle: Drivable {
		func start() {
			print("Starting bicycle")
		}
		
		func drive() {
			print("Riding bicycle")
		}
	}
	```

 	Here:

	- Both `Car` and `Bicycle` conform to the `Drivable` protocol.
	- They can share behavior without being related by inheritance.
 	<br />
	
	Key benefits of Protocol-Oriented Programming:

	- **Flexibility**: Any type (class, struct, or enum) can conform to a protocol, so we're not tied to a single class hierarchy.
 	- **Composition over inheritance**: We can "compose" multiple behaviors by conforming to multiple protocols, rather than relying on deep inheritance trees.
		```swift
		protocol Drivable {
			func drive()
		}
		
		protocol Flyable {
			func fly()
		}
		
		struct FlyingCar: Drivable, Flyable {
			func drive() {
				print("Driving on the road")
			}
			
			func fly() {
				print("Flying in the sky")
			}
		}
  		```
  	- **Value types**: Protocols work seamlessly with value types like struct and enum, which are preferred in Swift because they are safer (immutable by default) and more efficient.
  	- **Swift support**: It provides the following features to take advantage of this paradigm:
  		- Protocol extensions to implement a default behavior.
			```swift
			protocol Drivable {
				func start()
				func drive()
			}
			
			extension Drivable {
				func start() {
					print("Starting the vehicle")
				}
			}

  	 		struct Car: Drivable {
				func drive() {
					print("Driving car")
				}
			}
				
			let car = Car()
			car.start() // "Starting the vehicle"
			car.drive() // "Driving car"
  	 		```
  	 	- Protocol composition into a single requirement using `&`.
			```swift
			protocol Flyable {
				func fly()
			}
			
			protocol Drivable {
				func drive()
			}
			
			func useFlyingCar(vehicle: Flyable & Drivable) {
				vehicle.fly()
				vehicle.drive()
			}
  	  		```
	</details>

- 🟧 [What experience do you have of functional programming?](https://www.hackingwithswift.com/interview-questions/what-experience-do-you-have-of-functional-programming)
	<details>
		<summary>Answer</summary>

	The answer depends on your experience with functional programming. Here's how I would approach it:
	
	>I would say that I have a fair amount of experience with functional programming, as I have used languages that support functional programming, such as Scala, Swift and Kotlin. It is a programming paradigm that treats computation as the evaluation of mathematical functions and avoids changing state or mutable data. It focuses on using pure functions, immutable data, and function composition.
	>
 	>Here are the key concepts of this paradigm:
	>
 	>- **Pure deterministic functions**: Functions that have no side effects and return the same output for the same input.
	>- **First-class functions**: Functions are treated as values, which means that we can assign a function to a variable, pass it around as an argument, or return it from other functions.
	>- **Higher-order functions**: Functions that take one or more functions as arguments and can also return a function.
	>- **Immutability**: Once data is created, it cannot be changed.
 	><br />
	> 
	>Overall, this paradigm makes code more compositional, more predictable due to pure functions, more testable due to immutability, and easier to manage concurrency due to immutability.
	</details>

- 🟥 [Can you explain KVO, and how it's used on Apple's platforms?](https://www.hackingwithswift.com/interview-questions/can-you-explain-kvo-and-how-its-used-on-apples-platforms)
	<details>
		<summary>Answer</summary>

	Key-Value Observing (KVO) is a design pattern used in UIKit to observe changes to the properties of objects. With KVO, we can register an object to observe changes to the values of a specified property of another object, and receive a notification when the value of that property changes.

	To use KVO, we typically define an observer object and register it with the object that we want to observe. When the value of a property changes, the observed object sends a notification to the observer object, which can then take some action based on the new value.

	For example, let's say we have a `User` model that has a `name` property. We want to be notified whenever the name property changes so that we can update the user interface. To do this, we would follow these steps:

	1. Define the model (`User`) with a property that we want to observe (`name`).
 
		```swift
		import Foundation
		
		class User: NSObject {
			@objc dynamic var name: String
		
			init(name: String) {
				self.name = name
			}
		}
	   	```

		The `@objc dynamic` modifier is required for KVO to work. The `@objc` part allows Swift properties to be accessed from Objective-C runtime (which KVO relies on), and `dynamic` ensures that the property is available for runtime observation.

	2. Set up the observer to watch the property.

		```swift
		import UIKit
		
		class ViewController: UIViewController {
		
			var user: User!
			
			override func viewDidLoad() {
				super.viewDidLoad()
				
				// Create the User object
				user = User(name: "John Doe")
				
				// Register for KVO to observe the 'name' property
				user.addObserver(self, forKeyPath: #keyPath(User.name), options: [.new, .old], context: nil)
				
				// Change the name property
				user.name = "Jane Doe"
			}
			
			// This method will be called when the 'name' property changes
			override func observeValue(
  				forKeyPath keyPath: String?,
  				of object: Any?,
  				change: [NSKeyValueChangeKey : Any]?,
  				context: UnsafeMutableRawPointer?
  			) {
				if keyPath == #keyPath(User.name) {
					if let newValue = change?[.newKey] as? String {
						print("The name has changed to \(newValue)")
					}
				}
			}
			
			deinit {
				// Remove the observer when done
				user.removeObserver(self, forKeyPath: #keyPath(User.name))
			}
		}
		```

		Explanation:

		- `addObserver(_:forKeyPath:options:context:)`: This method registers the observer (`self`) to watch the `name` property on the `user` object. We specify the `keyPath` (which is the property name `name`), and we also specify that we want to receive both the new and old values when the property changes.
		- `observeValue(forKeyPath:of:change:context:)`: This is the method that gets called whenever the observed property changes. Here, we can check which key path was changed (`keyPath`), and take action based on the new value.
		- `removeObserver(_:forKeyPath:)`: This is very important. We must always remove observers when they are no longer needed to avoid memory leaks or unexpected behavior. In this case, we remove the observer in the `deinit` method to make sure it's cleaned up when the view controller is deallocated.
		<br />

	Overall, KVO can be useful in many situations, such as updating a UI when the value of a model object changes, or observing changes to a property of a third-party library. However, it's important to use KVO with care, as KVO notifications are usually delivered on the same thread that changes the observed property. When observing from a background thread, be sure to properly handle UI updates on the main thread. In addition, this process can be resource-intensive, especially when observing many properties. For large applications using UIKit, consider alternative patterns like `NSNotificationCenter` or **reactive programming**.
	</details>

- 🟥 [Can you give some examples of where singletons might be a good idea?](https://www.hackingwithswift.com/interview-questions/can-you-give-some-examples-of-where-singletons-might-be-a-good-idea)
	<details>
		<summary>Answer</summary>

	Singletons are commonly used in situations where there should only be a single instance of a particular object in the application, and that instance needs to be easily accessible from multiple parts of the codebase. Here are a few examples of where singletons might be a good idea:

	- **Network managers**: Managing network calls and handling sessions, which benefit from a single instance to avoid multiple network configurations and duplicated state.
	- **Database connections**: Creating a single connection to a database ensures efficient resource management and avoids conflicts or duplicated data handling.
	- **Logging**: A singleton logging service can track events and errors across the app from a central point.
	- **Analytics managers**: When collecting and sending analytics data, having a single instance to manage this flow ensures consistency and reduces potential duplicate entries.
	<br />  

	They should be used sparingly, as they can lead to tight coupling and make code harder to test.
	</details>

- 🟥 [What are phantom types and when would you use them?](https://www.hackingwithswift.com/interview-questions/what-are-phantom-types-and-when-would-you-use-them)
	<details>
		<summary>Answer</summary>

	Phantom types are types that are not instantiated with a value, but rather serve as a way to enforce constraints on a program's logic at compile time.

	For example, consider a function that performs an operation on two integers. We might want to enforce that the two integers have the same sign. We could use a phantom type to represent positive or negative integers, and then require that both arguments to the function have the same phantom type. This would ensure that the function can only be called with arguments of the same sign.

	Phantom types can also be used to enforce more complex constraints on data, such as ensuring that a value has been validated or that a value is only used in certain contexts. By using phantom types, we can ensure that certain properties of our program are enforced at compile time, rather than relying on runtime checks.

	Here's an example of phantom types:

	```swift
	struct Username<T>: ExpressibleByStringLiteral {
		let value: String

		init(stringLiteral value: String) {
			self.value = value
		}
	}
	
	struct Password<T>: ExpressibleByStringLiteral {
		let value: String

		init(stringLiteral value: String) {
			self.value = value
		}
	}
	
	struct User<U, P> {
		let username: U
		let password: P
	}
	
	// Create a user with a valid username and password
	let user = User(username: Username("johndoe"), password: Password("secretpassword"))
	
	// Attempt to create a user with an invalid password
	let invalidUser = User(username: Username("janedoe"), password: Password(12345)) // Compiler error: Cannot convert value of type 'Int' to expected argument type 'String'
	```
	
	In this example, we define two phantom types `Username` and `Password`, which are essentially just wrappers around `String`. We use these phantom types to create a `User` struct, which takes two generic type parameters `U` and `P` that represent the phantom types for the username and password, respectively.

	By using phantom types in this way, we can ensure that only valid strings are used to create a user. Attempting to create a user with an invalid password (in this case, an integer) will result in a compiler error.

	For more information, see this [Hacking with Swift](https://www.hackingwithswift.com/plus/advanced-swift/how-to-use-phantom-types-in-swift) post.
	</details>

<p align="right">(<a href="#top">back to top</a>)</p>

## Frameworks

- 🟩 [How does CloudKit differ from Core Data?](https://www.hackingwithswift.com/interview-questions/how-does-cloudkit-differ-from-core-data)
	<details>
		<summary>Answer</summary>

	CloudKit is a cloud-based solution provided by Apple that allows developers to store data and files in iCloud and share that data between devices. Core Data, on the other hand, is a framework that allows developers to manage the data model layer of an app, including storing and retrieving data from a persistent store.

	Some key differences between CloudKit and Core Data are:

	- **Internet connection**: CloudKit requires an Internet connection to send data to the cloud, whereas Core Data doesn't because it stores the data locally on the device.
 	- **Apple Developer Account**: CloudKit requires an Apple Developer Account, whereas Core Data doesn't.
	- **Data syncing**: CloudKit provides automatic syncing of data between devices, while Core Data requires developers to implement their own syncing solution. It's worth noting that Core Data can be combined with CloudKit to enable syncing using `NSPersistentCloudKitContainer`.
	- **Server-side processing**: CloudKit provides server-side processing of data using Cloud Functions, while Core Data does not have this capability.
 	- **Use cases**: CloudKit is better suited for apps that require real-time syncing and multi-user collaboration, such as shared notes, while Core Data is more appropriate for apps with complex data relationships that support caching, such as task trackers.
	<br />
	
	In summary, CloudKit is a cloud-based storage and syncing solution, while Core Data is a local data storage and management framework. Depending on the needs of an app, one or both of these technologies may be used.
	</details>

- 🟩 [How does SpriteKit differ from SceneKit?](https://www.hackingwithswift.com/interview-questions/how-does-spritekit-differ-from-scenekit)
	<details>
		<summary>Answer</summary>

	SpriteKit and SceneKit are both 2D and 3D graphics rendering frameworks, respectively, that are provided by Apple on its platforms. The main differences between them are:

	- **Use case**: SpriteKit is mainly used for 2D game development, whereas SceneKit is designed for 3D game and app development.
	- **Physics engine**: Both frameworks have built-in physics engines to simulate realistic movements and interactions between objects. However, SpriteKit's physics engine is more lightweight and designed for 2D games, while SceneKit's physics engine is more advanced and can handle more complex interactions in 3D environments.
	- **Animation tools**: SpriteKit provides a powerful set of tools for creating animations, including the ability to animate textures, colors, and other properties. SceneKit also has animation tools, but they are designed more for creating complex 3D animations with keyframe animation.
	- **Rendering pipeline**: The rendering pipeline in SpriteKit is optimized for 2D graphics, while SceneKit's pipeline is optimized for 3D graphics. This means that SpriteKit can handle large numbers of 2D sprites with ease, while SceneKit can handle complex 3D models and scenes.
	<br />

	The choice between SpriteKit and SceneKit depends on the specific needs of the project. For simple 2D games, SpriteKit is often the better choice due to its ease of use and performance. For more complex 3D games or apps, SceneKit provides a more robust set of tools for creating complex scenes and interactions.
	</details>

- 🟩 [How much experience do you have using Core Data? Can you give examples?](https://www.hackingwithswift.com/interview-questions/how-much-experience-do-you-have-using-core-data-can-you-give-examples)
	<details>
		<summary>Answer</summary>

	The answer depends on your experience with Core Data. Here's how I would approach it:
	
	>I would say that I have a fair amount of experience using Core Data. I have used it in the following projects:
	>
	>- A note-taking app that allows users to create and store notes. The notes were stored in the user's device using Core Data.
	>- A contacts app that allows users to manage their contacts. The contacts were store in the user's device using Core Data.
	>- An app that fetches GitHub users from remote and allows the user to favorite users, which were managed using Core Data.
	</details>

- 🟩 [How much experience do you have using Core Graphics? Can you give examples?](https://www.hackingwithswift.com/interview-questions/how-much-experience-do-you-have-using-core-graphics-can-you-give-examples)
	<details>
		<summary>Answer</summary>

	The answer depends on your experience with Core Graphics. Here's how I would approach it:
	
	>I would say that I have a fair amount of experience using Core Data. I have used it for the following purposes:
	>
	>- **Drawing charts and graphs**: I have used it to create shapes, lines, colors, and gradients in order to create complex charts and visualizations.
	>- **Image manipulation**: I have used it to crop, resize, rotate, and apply filters to images.
	>- **PDF generation**: I have use it to create custom PDF documents with text, images and shapes.
	>- **Drawing game graphics**: I have used it to draw game graphics in iOS games, such as sprites and particle effects.
	</details>

- 🟩 [What are the different ways of showing web content to users?](https://www.hackingwithswift.com/interview-questions/what-are-the-different-ways-of-showing-web-content-to-users)
	<details>
		<summary>Answer</summary>

	There are different ways of showing web content to users in Swift, including:

 	- **Opening a URL in the full Safari app**: This can be done `UIApplication.shared.open(url)`. It's a simple method that provides access to all Safari features, as it opens the safari app. However, it leaves the app and the app loses the control over the content.
 	- **Using `WKWebView`**: This is a native iOS class that allows us to embed a fully featured browser in our app. We can load any website or HTML content using the `load(_:)` method of `WKWebView`. We can also customize the web view's appearance and behavior using various properties and delegate methods, as well as executing JavaScript and working offline with local HTML.
	- **Using `SFSafariViewController`**: This is a built-in view controller that displays web content in Safari's user interface. We can use this view controller to show web pages, authenticate users with web-based services, and enable features such as Reader mode, content blockers, and more. This is an easy and secure way to display web content without worrying about implementing navigation or security features.
	- **Using `UIWebView`**: This is an older iOS class that is now deprecated and replaced by `WKWebView`. However, if we need to support older versions of iOS, we can still use `UIWebView` to display web content. The process is similar to using `WKWebView`, but the behavior and features of the web view may be different.
	<br />

	The choice of method depends on our specific needs and the level of control and customization required for the appearance and behavior of web content.
	</details>

- 🟩 [What class would you use to list files in a directory?](https://www.hackingwithswift.com/interview-questions/what-class-would-you-use-to-list-files-in-a-directory)
	<details>
		<summary>Answer</summary>

	In Swift, we can use the `FileManager` class to list files in a directory. The `contentsOfDirectory(atPath:)` method of `FileManager` returns an array of file and folder names within a given directory. Here's an example:

	```swift
	let fileManager = FileManager.default
	let documentsURL = try! fileManager.url(for: .documentDirectory, in: .userDomainMask, appropriateFor: nil, create: false)
	let directoryContents = try! fileManager.contentsOfDirectory(atPath: documentsURL.path)

	for item in directoryContents {
		print("Found item: \(item)")
	}
	```
	
	In this example, we first get the `FileManager` object, then we get the URL for the document directory using `url(for:in:appropriateFor:create:)`. We then use the `contentsOfDirectory(atPath:)` method to get an array of file and folder names within the document directory, and loop through them to print each item's name.
	</details>

- 🟩 [What is `UserDefaults` good for? What is `UserDefaults` not good for?](https://www.hackingwithswift.com/interview-questions/what-is-userdefaults-good-for-what-is-userdefaults-not-good-for)
	<details>
		<summary>Answer</summary>

	`UserDefaults` is a convenient way to store small amounts of user-related data such as preferences, settings, and configurations. It's essentially a key-value store that provides an interface for storing and retrieving data using simple API.

	✅ `UserDefaults` is useful for:

  	- Small, user-specific preferences and settings, such as the preferred language or theme.
	- Lightweight, non-critical data that doesn't change frequently.
	- Boolean flags, user states, and app configuration.
	<br />

	❌ `UserDefaults` is not a good choice for:

	- Large or complex data (use **Core Data**, **SQLite**, or **Realm** for this).
	- Long-term or relational data persistence (use **Core Data**, **SQLite**, or **Realm** for this).
	- Sensitive data that requires encryption or secure storage (use **Keychain** for this).
	</details>

- 🟩 [What is the purpose of `NotificationCenter`?](https://www.hackingwithswift.com/interview-questions/what-is-the-purpose-of-notificationcenter)
	<details>
		<summary>Answer</summary>

	The `NotificationCenter` class in Swift is a messaging system used to broadcast information within an app. It allows different parts of an app to communicate without tightly coupling them. When an event happens, one or more objects can post a notification to the notification center, which then broadcasts the notification to any interested observers.

	It is a powerful tool for decoupling different parts of an app. It is commonly used to handle situations such as updating the UI when a data model changes, responding to system events such as keyboard or screen orientation changes, and notifying other parts of the app when a user completes a task—like logging in or switching themes. However, it's not suitable for communication between unrelated apps, or for sharing large amounts of data between different parts of an app. In those cases, other mechanisms such as URL schemes or app extensions may be more appropriate.

	Observers can register with the `NotificationCenter` to receive notifications about specific events. When a notification is posted, the notification center sends the notification to all registered observers. The observers can then take appropriate action based on the content of the notification.

	Here's an example:

  	```swift
	// Payload (optional)
	let userInfo = ["newData": "Example Data"]

	// Post a notification with a payload to `NotificationCenter` to announce an event
	NotificationCenter.default.post(name: Notification.Name("DataUpdated"), object: nil, userInfo: userInfo)

	// Register observer for a specific notification
	NotificationCenter.default.addObserver(self, selector: #selector(handleDataUpdate), name: Notification.Name("DataUpdated"), object: nil)

	// Method that handles the `DataUpdated` notification
	@objc func handleDataUpdate(notification: Notification) {
		print("Data has been updated!")
	}
   	```
	</details>

- 🟩 [What steps would you follow to make a network request?](https://www.hackingwithswift.com/interview-questions/what-steps-would-you-follow-to-make-a-network-request)
	<details>
		<summary>Answer</summary>

	1. **Create the URL**

		```swift
		guard let url = URL(string: "https://api.example.com/data") else {
			print("Invalid URL")
			return
		}
		```

	2. **Create a `URLRequest`** (optional)

		If we need to customize the request (e.g., set HTTP method, headers):

		```swift
		var request = URLRequest(url: url)
		request.httpMethod = "GET"  // or "POST", "PUT", etc.
		request.setValue("application/json", forHTTPHeaderField: "Content-Type")
		```

	3. **Create a `URLSession`**

		This creates a data task to perform the request:

		```swift
		let task = URLSession.shared.dataTask(with: request) { data, response, error in
			// Handle the response here
		}
		```
		
	5. **Handle the response**

		```swift
		// Check for errors.
		if let error = error {
				print("Error: \(error.localizedDescription)")
				return
		}

		// Validate the HTTP response (status code).
		guard let httpResponse = response as? HTTPURLResponse,
				(200...299).contains(httpResponse.statusCode) else {
			print("Invalid response")
			return
		}

		// Make sure there is data.
		guard let data = data else {
			print("No data received")
			return
		}

		do {
			// Parse the data (e.g., JSON decoding).
			let decodedObject = try JSONDecoder().decode(MyModel.self, from: data)
			print("Decoded: \(decodedObject)")
		} catch {
			// Handle decoding error.
			print("Decoding error: \(error)")
		}
		```

	7. **Start the task**

		```swift
		task.resume()
		```

	9. **Bonus: Using `async/await`** (iOS 15+)

		```swift
		func fetchData() async {
			guard let url = URL(string: "https://api.example.com/data") else { return }
		
			do {
				let (data, response) = try await URLSession.shared.data(from: url)

				guard let httpResponse = response as? HTTPURLResponse,
							(200...299).contains(httpResponse.statusCode) else {
						print("Invalid response")
						return
				}

				let decodedObject = try JSONDecoder().decode(MyModel.self, from: data)
				print("Decoded: \(decodedObject)")
			} catch {
				print("Network error: \(error)")
			}
		}
		```

	<br>

	These are the basic steps to make a network request in an iOS app, but the specifics may vary depending on our app's requirements and the API we're interacting with.
	</details>

- 🟩 [When would you use `CGAffineTransform`?](https://www.hackingwithswift.com/interview-questions/when-would-you-use-cgaffinetransform)
	<details>
		<summary>Answer</summary>

	`CGAffineTransform` is a struct representing a two-dimensional affine transformation used in Core Graphics on Apple platforms such as iOS and macOS. It's used to perform graphical transformations such as rotating, scaling, translating, shearing, or combining multiple transformations into a single transformation on a view, image, or graphic.

	>An **affine transformation** preserves lines and parallelism. For example, a square might turn into a rectangle or parallelogram, but lines within the shape will remain straight, and parallel lines will stay parallel.

	Here's an example in UIKit that uses all of the above transformations:

	```swift
	let sqView = UIView(frame: CGRect(x: 100, y: 200, width: 100, height: 100))
	sqView.backgroundColor = .blue
	view.addSubview(sqView)
 
	sqView.transform = CGAffineTransform(rotationAngle: .pi / 4)			// rotation (in radians)
 	sqView.transform = CGAffineTransform(scaleX: 1.5, y: 1.5) 			// scaling (resizes the view)
 	sqView.transform = CGAffineTransform(translationX: 50, y: 100)			// translation (moves the view to a new position)
 	sqView.transform = CGAffineTransform(a: 1, b: 0, c: 0.5, d: 1, tx: 0, ty: 0)	// shearing (skews the view)
 	sqView.transform = CGAffineTransform(translationX: 50, y: 100)			// combining transformations
 				.scaledBy(x: 2.0, y: 2.0)
 				.rotated(by: .pi / 4)
	```

 	To use `CGAffineTransform` in SwiftUI, we need to use the `transformEffect` modifier. However, there are other modifiers to apply specific transformations without the need to use `CGAffineTransform`, such as `rotationEffect` or `scaleEffect`:
  
  	```swift
 	Rectangle()
		.fill(Color.blue)
		.frame(width: 100, height: 100)
		.transformEffect(CGAffineTransform(translationX: 50, y: 100))  // same visual translation as `.offset(x: 50, y: 100)`
		.rotationEffect(.degrees(45))
		.scaleEffect(CGSize(width: 1.5, height: 2))
		.overlay(Text("Transformed").foregroundColor(.white))
	```
	</details>

- 🟧 [How much experience do you have using Core Image? Can you give examples?](https://www.hackingwithswift.com/interview-questions/how-much-experience-do-you-have-using-core-image-can-you-give-examples)
	<details>
		<summary>Answer</summary>

	The answer depends on your experience with Core Image. Here's how I would approach it:

	>I would say that I have a fair amount of experience using Core Image. I have used it for the following purposes: 
	>
	>- **Enhancing photos**: I have used CoreImage to apply filters to photos, such as adjusting brightness, contrast, and saturation, or adding special effects like vignettes or blurs.
	>- **Real-time image analysis**: I have used it to perform real-time image analysis, such as detecting faces and facial features, tracking motion, or recognizing objects in a scene.
	>- **Applying filters to an image**:
	>
	>	```swift
	>	import CoreImage
	>	import UIKit
	>	
	>	let image = UIImage(named: "example.jpg")!
	>	let ciImage = CIImage(image: image)!
	>	
	>	let filter = CIFilter(name: "CISepiaTone")!
	>	filter.setValue(ciImage, forKey: kCIInputImageKey)
	>	filter.setValue(0.8, forKey: kCIInputIntensityKey)
	>	
	>	let context = CIContext()
	>	if let outputImage = filter.outputImage,
	>	   let cgImage = context.createCGImage(outputImage, from: outputImage.extent)
	>	{
	>	    let filteredImage = UIImage(cgImage: cgImage)
	>	    // Use filteredImage in an UIImageView, etc.
	>	}
	>	```
	</details>

- 🟧 [How much experience do you have using iBeacons? Can you give examples?](https://www.hackingwithswift.com/interview-questions/how-much-experience-do-you-have-using-ibeacons-can-you-give-examples)
	<details>
		<summary>Answer</summary>

	iBeacons are now deprecated, so I wouldn't bother preparing this question. However, I will provide its answer for the sake of completeness.

	The answer depends on your experience with iBeacons. Here's how I would approach it:
	
	>I haven't had much experience with it due to its low popularity. However, I once made a project to send notifications or special offers to customers who were browsing nearby products in a store.
	</details>

- 🟧 [How much experience do you have using StoreKit? Can you give examples?](https://www.hackingwithswift.com/interview-questions/how-much-experience-do-you-have-using-storekit-can-you-give-examples)
	<details>
		<summary>Answer</summary>
	
	The answer depends on your experience with StoreKit. Here's how I would approach it:
	
	>I integrated StoreKit into two applications. One was a game that used StoreKit to allow players to purchase new levels and characters, and the other was an English learning app that allowed users to subscribe to a monthly plan that gave them access to unlimited content within the app.
 	
 	Here are a few code examples to demonstrate your knowledge of StoreKit:
  
	1. **Fetching products from App Store**
		```swift
		import StoreKit
		class IAPManager: NSObject, SKProductsRequestDelegate {
			var products = [SKProduct]()
	
			func fetchProducts() {
				let productIdentifiers: Set<String> = ["com.example.app.coins100", "com.example.app.premium"]
				let request = SKProductsRequest(productIdentifiers: productIdentifiers)
				request.delegate = self
				request.start()
			}
	
			func productsRequest(_ request: SKProductsRequest, didReceive response: SKProductsResponse) {
				products = response.products
				for product in products {
					print("Product: \(product.localizedTitle), price: \(product.price)")
				}
			}
		}
		```
	
	2. **Purchasing a product**
		```swift
		func purchase(product: SKProduct) {
		let payment = SKPayment(product: product)
		SKPaymentQueue.default().add(payment)
		}
		```
	
		Don't forget to add yourself as a transaction observer:
		```swift
		SKPaymentQueue.default().add(self)
		```
	
		and implement transaction observer methods:
		```swift
		extension IAPManager: SKPaymentTransactionObserver {
			func paymentQueue(_ queue: SKPaymentQueue, updatedTransactions transactions: [SKPaymentTransaction]) {
				for transaction in transactions {
					switch transaction.transactionState {
					case .purchased:
						print("Purchase successful!")
						SKPaymentQueue.default().finishTransaction(transaction)
					case .failed:
						print("Purchase failed: \(transaction.error?.localizedDescription ?? "unknown error")")
						SKPaymentQueue.default().finishTransaction(transaction)
					case .restored:
						print("Purchase restored")
						SKPaymentQueue.default().finishTransaction(transaction)
					default:
						break
					}
				}
			}
		}
		```
	
	3. **Restoring purchases**
		```swift
		func restorePurchases() {
			SKPaymentQueue.default().restoreCompletedTransactions()
		}
		```
  
	</details>

- 🟧 [How much experience do you have with GCD?](https://www.hackingwithswift.com/interview-questions/how-much-experience-do-you-have-with-gcd)
	<details>
		<summary>Answer</summary>

	The answer depends on your experience with GCD. Here's how I would approach it:

	>Grand Central Dispatch (GCD) is Apple's low-level concurrency and threading API used in Swift to that abstracts thread management, making concurrency easier and safer. I have used it in multiple projects to perform time-consuming tasks in the background, such as network requests or file operations, without blocking the main thread and freezing the UI. I have used the main queue to handle UI-related tasks and global queues for general-purpose tasks.

	Here are a few code examples to demonstrate your knowledge of GCD:

	1. **Running a task asynchronously on a background queue**
		```swift
		DispatchQueue.global(qos: .background).async {
			// Do heavy work here

			DispatchQueue.main.async {
					// Update UI here
			}
		}
		```

	2. **Creating a custom serial queue**
		```swift
		let serialQueue = DispatchQueue(label: "com.example.mySerialQueue")
		serialQueue.async {
			// Tasks executed one by one in order
		}
		```

	3. **Using `DispatchGroup` to wait for multiple async tasks**
		```swift
		let group = DispatchGroup()

		group.enter()
		DispatchQueue.global().async {
			// Task 1
			group.leave()
		}

		group.enter()
		DispatchQueue.global().async {
			// Task 2
			group.leave()
		}

		group.notify(queue: DispatchQueue.main) {
			print("Both tasks finished")
		}
		```

	4. **Using a `DispatchSemaphore` to limit concurrency**
		```swift
		let semaphore = DispatchSemaphore(value: 2) // Limit to 2 concurrent tasks

		DispatchQueue.global().async {
			semaphore.wait()
			// Perform task
			semaphore.signal()
		}
		```		
	</details>

- 🟧 [What class would you use to play a custom sound in your app?](https://www.hackingwithswift.com/interview-questions/what-class-would-you-use-to-play-a-custom-sound-in-your-app)
	<details>
		<summary>Answer</summary>

	I would use the `AVAudioPlayer` class in Swift. It's designed for playing audio files from an app bundle or the file system. It supports formats such as `.mp3`, `.wav`, `.m4a`, etc. and allows control over playback (play, pause, and stop).

	Here's an example code snippet that shows how to play a sound file named `mySoundFile.mp3` from the app's main bundle:

	```swift
	import AVFoundation

	func playSound() {
		guard let url = Bundle.main.url(forResource: "mySoundFile", withExtension: "mp3") else { return }
		do {
			let player = try AVAudioPlayer(contentsOf: url)
			player.prepareToPlay()
			player.play()
		} catch let error {
			print(error.localizedDescription)
		}
	}
	```
	
	This code loads the sound file URL from the app's main bundle using `Bundle.main.url(forResource:withExtension:)`, creates an instance of `AVAudioPlayer`, prepares it for playback with `prepareToPlay()`, and starts playback with `play()`. If an error occurs, it is printed to the console.
	</details>

- 🟧 [What experience do you have of `NSAttributedString`?](https://www.hackingwithswift.com/interview-questions/what-experience-do-you-have-of-nsattributedstring)
	<details>
		<summary>Answer</summary>

	The answer depends on your experience with `NSAttributedString`. Here's how I would approach it:

	>`NSAttributedString` is a class used to create immutable (read-only) strings with rich text attributes (like fonts, colors, styles, etc.) attached to ranges of characters. I have used it to display stylized text in views, such as `UILabel`, `UIButton` and `UITextView`. It is useful for creating headings, bullet points or highlighted text.

	Here's a code example for creating a `NSAttributedString`:

	```swift
	let attributedString = NSMutableAttributedString(string: "Hello, World!")

	// Make "Hello" bold
	attributedString.addAttribute(.font, value: UIFont.boldSystemFont(ofSize: 18), range: NSRange(location: 0, length: 5))

	// Make "World" red
	attributedString.addAttribute(.foregroundColor, value: UIColor.red, range: NSRange(location: 7, length: 5))
	```
	</details>

- 🟧 [What is the purpose of GameplayKit?](https://www.hackingwithswift.com/interview-questions/what-is-the-purpose-of-gameplaykit)
	<details>
		<summary>Answer</summary>

	GameplayKit is a framework provided by Apple for building games in Swift. It includes a variety of tools and functionalities to help developers create games quickly and efficiently. Some features offered by GameplayKit include pathfinding, randomization, state machines, and artificial intelligence.

	The framework can be used to create both 2D and 3D games, and includes built-in support for popular game engines like SpriteKit and SceneKit. Additionally, GameplayKit provides support for physics simulations, which can be useful for creating realistic game mechanics.

	All in all, the purpose of GameplayKit is to simplify game development by providing a range of tools and functionalities that can be used to create a wide variety of games with minimal effort.
	</details>

- 🟧 [What is the purpose of ReplayKit?](https://www.hackingwithswift.com/interview-questions/what-is-the-purpose-of-replaykit)
	<details>
		<summary>Answer</summary>

	ReplayKit is a framework provided by Apple for recording and sharing gameplay videos, app demos, or any other on-screen content. It allows users to record their screens while using an app, and then share the resulting video with others. ReplayKit also includes APIs for live broadcasting, which allows users to stream their gameplay or app usage in real-time to viewers on popular streaming platforms like Twitch or YouTube.

	ReplayKit provides a number of features to developers, including:

	- Recording and sharing of app content
	- Configurable recording settings, including video quality, frame rate, and audio options
	- Support for recording both audio and video
	- Support for live broadcasting to popular streaming platforms
	- Built-in support for sharing recorded videos via social media, messaging apps, and more
	<br />

	Here's a basic example for starting a recording:

	```swift
	import ReplayKit

	let recorder = RPScreenRecorder.shared()

	func startRecording() {
		recorder.isMicrophoneEnabled = true
		recorder.startRecording { error in
			if let error = error {
				print("Recording failed: \(error.localizedDescription)")
			} else {
				print("Recording started")
			}
		}
	}
	```

 	And stopping the recording:

	```swift
	recorder.stopRecording { previewVC, error in
		if let previewVC = previewVC {
			previewVC.previewControllerDelegate = self
			// Present the preview so user can trim, save, or share
			present(previewVC, animated: true)
		}
	}
 	```
	
	In short, ReplayKit is a useful tool for developers who want to give their users an easy way to share their app experiences with others, or for those who want to incorporate gameplay or app demo videos into their marketing efforts.
	</details>

- 🟧 [When might you use `NSSortDescriptor`?](https://www.hackingwithswift.com/interview-questions/when-might-you-use-nssortdescriptor)
	<details>
		<summary>Answer</summary>

	We might use `NSSortDescriptor` when we need to sort an array of objects based on one or more properties of those objects. `NSSortDescriptor` provides a flexible way to sort arrays, allowing us to sort based on a single property or multiple properties, and specify the order in which they should be sorted (ascending or descending). We can use `NSSortDescriptor` with many of the Foundation classes, including `NSArray`, `NSMutableArray`, `NSSet`, and `NSMutableSet`.

	For example, if we have an array of `Person` objects and we want to sort them by their name property, we could create an `NSSortDescriptor` with a key of `"name"` and use it to sort the array:

	```swift 
	let people = [Person(name: "Alice"), Person(name: "Bob"), Person(name: "Charlie")]
	let sortDescriptor = NSSortDescriptor(key: "name", ascending: true)
	let sortedPeople = (people as NSArray).sortedArray(using: [sortDescriptor]) as! [Person]
	```

	This would sort the array of people in ascending order based on their `name` property.

	It is also useful for sorting Core Data fetch results by passing in `NSSortDescriptor`s to determine the sort order:

	```swift
	let request = NSFetchRequest<Person>(entityName: "Person")
	let sortByName = NSSortDescriptor(key: "lastName", ascending: true, selector: #selector(NSString.localizedCaseInsensitiveCompare(_:)))
	request.sortDescriptors = [sortByName]
 	```

 	It's encoraged to use `NSSortDescriptor` instead of a Sort cloure because it's more declarative and works well with Objective-C APIs like `NSArray`. Moreover, it's required for Core Data fetches and makes sorting logic reusable and composable.
	</details>

- 🟥 [Can you name at least three different `CALayer` subclasses?](https://www.hackingwithswift.com/interview-questions/can-you-name-at-least-three-different-calayer-subclasses)
	<details>
		<summary>Answer</summary>

	Yes, these are three different subclasses of `CALayer`:

	- `CAShapeLayer`: This subclass is used to draw vector shapes, like circles or polygons, with various fill and stroke options.
	- `CATextLayer`: This subclass is used to render text in a layer, with options for font, color, and alignment.
	- `CAEmitterLayer`: This subclass is used to create particle effects, like fire or snow, by emitting and animating a large number of small images.
	</details>

- 🟥 [What is the purpose of `CADisplayLink`?](https://www.hackingwithswift.com/interview-questions/what-is-the-purpose-of-cadisplaylink)
	<details>
		<summary>Answer</summary>

	`CADisplayLink` is a class in UIKit that creates a timer that synchronizes your app's rendering with the display's refresh rate (usually 60 or 120 Hz on modern iOS devices). When a `CADisplayLink` object is added to the app's run loop, the system notifies the app each time the display is about to refresh. This allows the app to update its content before the screen is redrawn, ensuring smooth and fluid animations.

	Here's an example of how it's used:

	```swift
	var displayLink: CADisplayLink?

	func startDisplayLink() {
		displayLink = CADisplayLink(target: self, selector: #selector(updateFrame))
		displayLink?.add(to: .main, forMode: .default)
	}

	@objc func updateFrame() {
		// Update animation frame, move objects, or redraw view
	}
	```

	`CADisplayLink` is commonly used in game development and other apps with complex graphics or animations.
	</details>

<p align="right">(<a href="#top">back to top</a>)</p>

## iOS

- 🟩 [How do you create your UI layouts – storyboards or in code?](https://www.hackingwithswift.com/interview-questions/how-do-you-create-your-ui-layouts-storyboards-or-in-code)
	<details>
		<summary>Answer</summary>

	The answer depends on your preference for creating UI layouts. Here's how I would approach it:

	>I prefer creating them in code because it gives me more flexibility and control over the layout, which is useful for more complex and dynamic UIs. It's also easier to manage with version control and refactoring, especially with the introduction of SwiftUI and its declarative approach, which makes building layouts easier and more intuitive than with UIKit. Storyboards, on the other hand, are faster to prototype and easily support segues and Auto Layout constraints. However, they are prone to merge conflicts, and it's difficult to reuse views or create complex, dynamic UIs.
	</details>

- 🟩 [How would you add a shadow to one of your views?](https://www.hackingwithswift.com/interview-questions/how-would-you-add-a-shadow-to-one-of-your-views)
	<details>
		<summary>Answer</summary>
	
	To add a shadow to a view in iOS, we can use the `layer` property of the view's `CALayer` object.

	Here's an example of how to add a shadow to a view:

	```swift 
	// Create the view
	let myView = UIView(frame: CGRect(x: 0, y: 0, width: 200, height: 200))
	
	// Set the shadow properties
	myView.layer.shadowColor = UIColor.black.cgColor
	myView.layer.shadowOpacity = 0.5
	myView.layer.shadowOffset = CGSize(width: 2, height: 2)
	myView.layer.shadowRadius = 4
	
	// Add the view to the parent view
	parentView.addSubview(myView)
	```
	
	In this example, we first create a new `UIView` with a frame of 200x200. We then set the `shadowColor` to black, `shadowOpacity` to 0.5 (semi-transparent), `shadowOffset` to (2, 2) to position the shadow below and to the right of the view, and `shadowRadius` to 4 to give the shadow a blur effect. Finally, we add the view to a parent view.

	Note that when adding a shadow to a view, it's important to set the view's `clipsToBounds` property to `false` to allow the shadow to be visible outside the view's bounds.
	</details>

- 🟩 [How would you round the corners of one of your views?](https://www.hackingwithswift.com/interview-questions/how-would-you-round-the-corners-of-one-of-your-views)
	<details>
		<summary>Answer</summary>

	To round the corners of a view, we can use the `cornerRadius` property of the view's layer. Here's an example of how to do it:

	```swift
	// Set the corner radius
	myView.layer.cornerRadius = 10
	
	// Clip to bounds to ensure the corners are rounded
	myView.clipsToBounds = true
	```
	
	This code sets the `cornerRadius` property of `myView`'s layer to 10, which rounds the corners. It also sets the `clipsToBounds` property to true to ensure that any content outside the rounded corners is clipped.
	</details>

- 🟩 [What are the advantages and disadvantages of SwiftUI compared to UIKit?](https://www.hackingwithswift.com/interview-questions/what-are-the-advantages-and-disadvantages-of-swiftui-compared-to-uikit)
	<details>
		<summary>Answer</summary>

	Advantages of SwiftUI compared to UIKit:

	- **Declarative syntax**: SwiftUI uses a declarative syntax, which makes it easier to read and write code. Instead of describing the steps to create a UI, we simply declare the desired UI components and their properties, and SwiftUI takes care of the implementation details.
	- **Preview canvas**: With SwiftUI, we can see a live preview of our UI as we create it. This helps us to quickly iterate on our design and catch any issues before compiling and running the app.
	- **Cross-platform development**: SwiftUI can be used to build user interfaces for multiple platforms, including iOS, macOS, watchOS, and tvOS, with a single codebase. This can save time and reduce development costs for applications that need to be deployed on multiple platforms.
	- **Better state management**: Built-in `@State`, `@Binding`, `@ObservedObject` make managing UI state reactive and easier to reason about.
	- **Accessibility**: SwiftUI includes accessibility features such as VoiceOver and dynamic type, which makes it easier to build apps that are accessible to everyone.
	<br />

	Disadvantages of SwiftUI compared to UIKit:

	- **Less documentation and community support**: Compared to UIKit, which has over a decade of documentation, tutorials, and StackOverflow questions, SwiftUI still lags.
	- **Limited feature set**: SwiftUI is a newer technology compared to UIKit, so it doesn't yet have the same level of features and flexibility as UIKit.
	- **Limited backwards compatibility**: SwiftUI requires a minimum deployment target of iOS 13 or macOS 10.15, which means that it can't be used for apps that need to support older operating systems.
	</details>

- 🟩 [What do you think is a sensible minimum iOS deployment target?](https://www.hackingwithswift.com/interview-questions/what-do-you-think-is-a-sensible-minimum-ios-deployment-target)
	<details>
		<summary>Answer</summary>

	The minimum iOS deployment target should depend on the needs of the app and the user base. Generally, it's recommended to support at least the last two or three major versions of iOS to ensure that the app is compatible with a large number of devices. However, if the app has specific requirements that are only available in the latest version of iOS, then the minimum deployment target may need to be higher.
 
	Additionally, it's important to consider the distribution of the user base when determining the minimum deployment target. If the majority of the users are on older devices or operating systems, it may be necessary to set a lower minimum deployment target to ensure that the app is accessible to as many users as possible.
	</details>

- 🟩 [What features of recent iOS versions were you most excited to try?](https://www.hackingwithswift.com/interview-questions/what-features-of-recent-ios-versions-were-you-most-excited-to-try)
	<details>
		<summary>Answer</summary>

	As for iOS 16, `NavigationView` is replaced by `NavigationStack` and `NavigationSplitView`, which sensibly improves the navigation handling in SwiftUI, which was kind of tricky compared to UIKit.
	</details>

- 🟩 [What kind of settings would you store in your `Info.plist` file?](https://www.hackingwithswift.com/interview-questions/what-kind-of-settings-would-you-store-in-your-info-plist-file)
	<details>
		<summary>Answer</summary>

	The `Info.plist` (Information Property List) file in an iOS app contains metadata that the system uses to configure and manage the app. It stores app settings and configuration keys that the OS or certain APIs need at runtime. The `Info.plist` file contains key-value pairs describing various aspects of the app, including as its name, version number, icon files, supported devices, required capabilities, and much more.
		
	Some examples of settings that can be stored in the `Info.plist` file include:

	- `CFBundleDisplayName`: App name
	- `CFBundleIdentifier`: App identifier
	- `CFBundleVersion`: App version
	- `UISupportedInterfaceOrientations`: Supported device orientations
	- `UIRequiredDeviceCapabilities`: Required device capabilities
	- `UIBackgroundModes`: Required background modes
	- `UILaunchStoryboardName`: App icons and launch images
	- `CFBundleURLTypes`: URL schemes
	- `CFBundleDocumentTypes`: Document types
	- `NSCameraUsageDescription`: Required camera permissions
	- `CFBundleDevelopmentRegion`: Localizations and language settings
	- `NSAppTransportSecurity`: App transport security settings
	- `CFBundleDocumentTypes`: Supported audio and video formats
	<br />

	In a nutshell, the `Info.plist` file is a powerful tool for configuring our app and communicating its requirements and capabilities to the system.
	</details>

- 🟧 [What is the purpose of size classes?](https://www.hackingwithswift.com/interview-questions/what-is-the-purpose-of-size-classes)
	<details>
		<summary>Answer</summary>

	In Swift, size classes provide a way to design responsive interfaces that can adapt to different device sizes and orientations. Using size classes, developers can define layout constraints and rules that automatically adjust based on the screen size of the device, enabling the creation of adaptive layouts that work across a wide range of devices.

	Size classes are defined by two dimensions: horizontal size class and vertical size class. The horizontal size class describes the width of the device's screen, and the vertical size class describes the height. Each size class can be set to one of several possible values, such as compact or regular, depending on the screen size.

	By using size classes in Swift, developers can create layouts that adjust dynamically based on the device's size and orientation, reducing the need to create separate layouts for different device sizes. This can make development more efficient and help ensure a consistent user experience across different devices.
	</details>

- 🟥 [What happens when `Color` or `UIColor` has values outside 0 to 1?](https://www.hackingwithswift.com/interview-questions/what-happens-when-color-or-uicolor-has-values-outside-0-to-1)
	<details>
		<summary>Answer</summary>

	In the old days, values outside of 0 and 1 were clamped, or forced to 0 or 1, because they were meaningless. However, A standard sRGB color space clamps each color component—`red`, `green`, and `blue`—to a range of 0 to 1, but SwiftUI colors use an extended sRGB color space, so you can use component values outside that range. This makes it possible to create colors using the `Color.RGBColorSpace.sRGB` or `Color.RGBColorSpace.sRGBLinear` color space that make full use of the wider gamut of a diplay that supports `Color.RGBColorSpace.displayP3`.
	</details>

<p align="right">(<a href="#top">back to top</a>)</p>

## Miscellaneous

- 🟩 [Can you talk me through some interesting code you wrote recently?](https://www.hackingwithswift.com/interview-questions/can-you-talk-me-through-some-interesting-code-you-wrote-recently)
	<details>
		<summary>Answer</summary>

	This question is broad and specific to the person being asked. However, here's an extensive answer talking about animations:

	>Recently, I worked on an iOS app that required a custom view that would animate the transition between two child views. This view needed to perform a series of animations in a specific order, with some animations happening simultaneously and others happening sequentially. To accomplish this, I created a custom animation manager class that used Core Animation to perform the animations.
	>
	>The animation manager class had a public function that could be called to start the animation. This function took two views as parameters: the current view and the view that was going to be displayed after the animation was complete.
	>
	>Inside the animation manager class, I used a combination of `CABasicAnimation` and `CAAnimationGroup` to perform the animations. I also used a completion block to make sure that the new view was added to the screen hierarchy at the correct time.
	>
	>One of the challenges with this code was making sure that the animations were performant and didn't cause any dropped frames or other issues. To do this, I used a combination of profiling tools and manual testing to make sure that the animations were smooth and didn't cause any performance problems.
	>
	>I was happy with how this code turned out. It was a great learning experience for me to work with Core Animation in Swift.
	</details>

- 🟩 [Do you have any favorite Swift newsletters or websites you read often?](https://www.hackingwithswift.com/interview-questions/do-you-have-any-favorite-swift-newsletters-or-websites-you-read-often)
	<details>
		<summary>Answer</summary>

	This question is specific to the person being asked. However, here's what I would answer:
	
	>I access a bunch of sites to strengthen my Swift knowledge but my favourite ones are [Swift by Sundell](https://www.swiftbysundell.com) and [Hacking with Swift](https://www.hackingwithswift.com). As for newsletters, my favourite one is [iOS Dev Weekly](https://iosdevweekly.com/).   
	</details>

- 🟩 [How do you stay up to date with changes in Swift?](https://www.hackingwithswift.com/interview-questions/how-do-you-stay-up-to-date-with-changes-in-swift)
	<details>
		<summary>Answer</summary>
	
	This question is specific to the person being asked. However, here's what I would answer:
	
	>I make sure to check the Swift documentation and release notes regularly to see what changes have been made in each new version of the language. I also keep an eye on any announcements made each year at WWDC, as well as visiting websites focused on Swift content, such as [Swift by Sundell](https://www.swiftbysundell.com) and [Hacking with Swift](https://www.hackingwithswift.com).
	</details>

- 🟩 [How familiar are you with XCTest? Have you ever created UI tests?](https://www.hackingwithswift.com/interview-questions/how-familiar-are-you-with-xctest-have-you-ever-created-ui-tests)
	<details>
		<summary>Answer</summary>

	This question is specific to the person being asked. However, here's what I would answer:
	
	>I'm very familiar with XCTest as it's a testing framework built into Xcode for unit testing. I have created UI tests by using the `XCUIApplication` API to launch the app and, then, using `XCUIElement` API to simulate user interactions with the UI, such as tapping buttons. Once this is settled, I use assertions to verify the expected behavior of the UI elements, such as checking if a label displays the correct text or if a button is enabled or disabled.
	>
	>Here's the code that reflects the process:
	>
	>```swift
	>import XCTest
	>
	>class MyAppUITests: XCTestCase {
	>
	>	var app: XCUIApplication!
	>
	>	override func setUp() {
	>		super.setUp()
	>		continueAfterFailure = false
	>
	>		app = XCUIApplication()
	>		app.launch()
	>	}
	>
	>	func testButtonTapUpdatesLabel() {
	>		// Simulate a user tapping a button
	>		let button = app.buttons["SubmitButton"]
	>		XCTAssertTrue(button.exists, "Submit button should exist")
	>		XCTAssertTrue(button.isEnabled, "Submit button should be enabled")
	>		button.tap()
	>
	>		// Verify that a label updates after tapping the button
	>		let label = app.staticTexts["StatusLabel"]
	>		XCTAssertTrue(label.exists, "Status label should exist")
	>		XCTAssertEqual(label.label, "Submission Successful", "Label should display success message")
	>	}
	>
	>	func testButtonIsDisabledInitially() {
	>		// Verify that a button is disabled on app launch
	>		let button = app.buttons["SubmitButton"]
	>		XCTAssertTrue(button.exists)
	>		XCTAssertFalse(button.isEnabled, "Submit button should be disabled at launch")
	>	}
	>}
	>```

	</details>

- 🟩 [How has Swift changed since it was first released in 2014?](https://www.hackingwithswift.com/interview-questions/how-has-swift-changed-since-it-was-first-released-in-2014)
	<details>
		<summary>Answer</summary>

	Since its first release in 2014, Swift has undergone significant changes and improvements. Some key changes include:

	- **ABI Stability**: One of the most significant changes was the introduction of ABI (Application Binary Interface) stability with Swift 5.0. This enabled developers to write code in Swift that could be distributed as binary frameworks, making it easier to use Swift code in projects and reducing the size of binary files.
	- **Language evolution**: Swift has continued to evolve, with new features and improvements introduced with each new release. Some notable additions include better error handling, enhanced optionals, protocol extensions, and a more powerful switch statement.
	- **Open source**: Swift was open-sourced in 2015, which enabled developers to contribute to the language and the community to grow. Since then, Swift has become one of the fastest-growing programming languages, and many companies and organizations have adopted it for their projects.
	- **Tooling and ecosystem growth**: The Swift tooling and infrastructure have also seen significant improvements over the years, making it easier to build, test, and distribute Swift code. This includes improvements to Xcode, the Swift Package Manager, and the introduction of SwiftUI.
	</details>

- 🟩 [If you could have Apple add or improve one API, what would it be?](https://www.hackingwithswift.com/interview-questions/if-you-could-have-apple-add-or-improve-one-api-what-would-it-be)
	<details>
		<summary>Answer</summary>
	
	This question is specific to the person being asked. However, here's what I would answer:
	
	>I would like Apple to improve the Camera API to provide more advanced control over the camera hardware and more flexibility for customizing the camera interface. It would be nice to have more granular control over camera settings like shutter speed, ISO, and focus, and more powerful tools for working with live camera feeds and AR technologies. 
	</details>

- 🟩 [What books would you recommend to someone who wants to learn Swift?](https://www.hackingwithswift.com/interview-questions/what-books-would-you-recommend-to-someone-who-wants-to-learn-swift)
	<details>
		<summary>Answer</summary>

	This question is specific to the person being asked. However, here's what I would answer:
	
	>I found the books by Hacking with Swift and Apple's "The Swift Programming Language" very useful to learn Swift, so I think they are a good starting point for a beginner.
	</details>

- 🟩 [What non-Apple apps do you think have particular good design?](https://www.hackingwithswift.com/interview-questions/what-non-apple-apps-do-you-think-have-particular-good-design)
	<details>
		<summary>Answer</summary>

	This question is specific to the person being asked. However, here's what I would answer:

	>I particularly like Spotify, which has a sleek and user-friendly design, making it easy for users to discover new music and create playlists. Duolingo is also an app with an excellent design because it combines a fun, colorful design with effective learning techniques.
	</details>

- 🟩 [What open source projects have you contributed to?](https://www.hackingwithswift.com/interview-questions/what-open-source-projects-have-you-contributed-to)
	<details>
		<summary>Answer</summary>

	This question is specific to the person being asked. However, here's what I would answer:

	>I have created open source projects that you can check on my GitHub account. Moreover, I have submitted pull requests that were merged into some projects such as Alamofire.
	</details>

- 🟩 [What process do you take to perform code review?](https://www.hackingwithswift.com/interview-questions/what-process-do-you-take-to-perform-code-review)
	<details>
		<summary>Answer</summary>

	This question is specific to the person being asked. However, here's what I would answer:
	
	>1. **Understand the context**: Before starting the code review, it's important to understand the context of the code changes. What problem is the code trying to solve, what's the expected outcome, and who is the target audience? Knowing this information will help us focus on the most critical aspects of the code.
	>2. **Check the code style**: It's important to check if the code is following the coding style guidelines. This includes things like naming conventions, code formatting, and commenting standards. Consistency is important, and it makes the code more readable and easier to maintain.
	>3. **Test the code**: Make sure the code works as intended. Test different scenarios, and try to identify edge cases that might break the code. If we find a bug, report it, and suggest a fix.
	>4. **Check for code quality**: Analyze the code for quality issues like complexity, duplication, and maintainability. Identify areas that could be improved, and suggest solutions to the problems we find.
	>5. **Provide constructive feedback**: Provide feedback that is constructive, objective, and actionable. Use examples to illustrate our point, and suggest alternative solutions where appropriate. Avoid being overly critical or dismissive, and keep the feedback focused on improving the code.
	>6. **Approve or request changes**: Approve if the code is ready to merge or request changes with clear guidance. Block only for correctness, security or design issues; not style nitpicks.
 	>7. **Follow up**: After the code review, follow up with the developer to make sure they understood our feedback and have addressed the issues we raised. Encourage them to ask questions if they need clarification, and be open to discussing any concerns they might have.
	</details>

- 🟧 [Have you ever filed bugs with Apple? Can you walk me through some?](https://www.hackingwithswift.com/interview-questions/have-you-ever-filed-bugs-with-apple-can-you-walk-me-through-some)
	<details>
		<summary>Answer</summary>
	
	This question is specific to the person being asked. However, here's what I would answer:
	
	>Yes, I have filed quite a few. To file a bug with Apple, we need to have an Apple ID and access to the Apple Bug Reporter website. Once we have logged in, we can create a new bug report and provide the following information:
	>
	>1. **Summary**: A brief description of the issue.
	>2. **Steps to Reproduce**: A detailed list of steps that reproduce the issue. Include any relevant data, such as sample code or screenshots.
	>3. **Expected Results**: A description of what we expected to happen.
	>4. **Actual Results**: A description of what actually happened.
	>5. **Version**: The version of the software we were using when the issue occurred.
	>6. **Configuration**: Any relevant configuration information, such as device type or operating system version.
	>7. **Notes**: Any additional information that may be helpful in reproducing the issue.
	</details>

- 🟧 [Have you ever used test- or business-driven development?](https://www.hackingwithswift.com/interview-questions/have-you-ever-used-test-or-business-driven-development)
	<details>
		<summary>Answer</summary>

	This question is specific to the person being asked. However, here's what I would answer:

	>Yes, I have used both. TDD (Test-Driven Development) is a valuable skill as a programmer because it helps us, the developers, to create high-quality code that is easier to maintain and modify over time.
	>As for BDD (Business-Driven Development), I have used it along with TDD to align software development with business objectives because BDD involves defining the desired behaviour of the software in terms of business requirements and then writing tests to ensure that the software meets those requirements. It is useful for making developers, testers, and non-technical people ensure that the software meets the business needs.  
	</details>

- 🟧 [How do you think Swift compares to Objective-C?](https://www.hackingwithswift.com/interview-questions/how-do-you-think-swift-compares-to-objective-c)
	<details>
		<summary>Answer</summary>

	Swift and Objective-C are both programming languages used for developing applications for Apple's ecosystem, with Objective-C being the older language and Swift being the newer one. Here are a few key differences:

	- **Syntax**: One of the most noticeable differences between Swift and Objective-C is their syntax. Swift uses a more modern, concise, and readable syntax than Objective-C, which can be more verbose and difficult to read.
	- **Performance**: Objective-C is less performant than Swift because it has a dynamic message resolution mechanism. That is, for every function call we do, Objective-C will look into a resolution table an it will decide on runtime where to send the message. Both Swift and Objective-C use ARC, so memory management is basically equivalent for both, except that Objective-C passes everything by reference, which may be slightly faster but very error prone. In contrast, Swift passes everything that is not a class by copy, except for data containers that uses the COW strategy. That is, Copy On Write, where instances are only copied when they are locally modified. That makes Swift safer and more performant than Objective-C.
	- **Safety**: Swift is designed to be a safer language than Objective-C. It has features like optional types and safe memory management that help prevent common programming errors.
	- **Interoperability**: Objective-C and Swift are interoperable, which means that we can use them together in the same project. This is particularly useful when we're migrating an existing Objective-C codebase to Swift.
	<br />
	
	Swift is a more modern and powerful language than Objective-C, and is increasingly becoming the language of choice for iOS and macOS development. However, Objective-C is still widely used and is a valuable skill to have as an iOS developer.
	</details>

- 🟧 [How familiar are you with Objective-C? Have you shipped any apps using it?](https://www.hackingwithswift.com/interview-questions/how-familiar-are-you-with-objective-c-have-you-shipped-any-apps-using-it)
	<details>
		<summary>Answer</summary>
	
	This question is specific to the person being asked. However, here's what I would answer:
	
	>I'm not familiar with Objective-C at all. All the projects I have worked on have been written entirely in Swift.
	</details>

- 🟧 [What experience do you have with the Swift Package Manager?](https://www.hackingwithswift.com/interview-questions/what-experience-do-you-have-with-the-swift-package-manager)
	<details>
		<summary>Answer</summary>

	This question is specific to the person being asked. However, here's what I would answer:
	
	>I have been using SPM (Swift Package Manager) since I started iOS development 3 years ago. However, for some larger projects, I have had to use CocoaPods instead due to its larger library of third-party dependencies. However, SPM is lighter and easier to integrate into Xcode, and more and more CocoaPods are being ported to SPM, so I have been using it more lately.   
	</details>

- 🟧 [What experience do you have working on macOS, tvOS, and watchOS?](https://www.hackingwithswift.com/interview-questions/what-experience-do-you-have-working-on-macos-tvos-and-watchos)
	<details>
		<summary>Answer</summary>

	This question is specific to the person being asked. However, here's what I would answer:

	>Not much at the moment. However, I would like to port some iOS apps to macOS and give tvOS and watchOS a try, but unfortunately not having the hardware is an obstacle to developing apps for these two platforms.
	</details>

- 🟧 [What is the purpose of code signing in Xcode?](https://www.hackingwithswift.com/interview-questions/what-is-the-purpose-of-code-signing-in-xcode)
	<details>
		<summary>Answer</summary>

	Code signing is a security mechanism in Xcode that ensures that the app or framework being installed on a device or submitted to the App Store is created by a trusted source and has not been modified since it was built. Code signing uses digital certificates and private keys to sign the app or framework, and the operating system checks the signature before allowing it to run.

	There are several reasons why code signing is important:

	- It ensures that the app or framework was created by a trusted source, which helps prevent malware and other security threats.
	- It verifies that the app or framework has not been tampered with since it was built, which helps prevent piracy and ensures the integrity of the code.
	- It allows the app or framework to access certain features and resources on the device, such as the camera or contacts, that would otherwise be restricted for security reasons.
	</details>

<p align="right">(<a href="#top">back to top</a>)</p>

## Performance

- 🟧 [How would you identify and resolve a retain cycle?](https://www.hackingwithswift.com/interview-questions/how-would-you-identify-and-resolve-a-retain-cycle)
	<details>
		<summary>Answer</summary>
	
	A retain cycle occurs when two or more objects hold strong references to each other, creating a situation where they can't be deallocated by ARC (Automatic Reference Counting) and leading to a memory leak. Here are the steps to identify and resolve a retain cycle:

	1. **Identify the objects involved**: The first step is to identify the objects involved in the retain cycle. We can use Xcode's memory debugger, Instruments, to track down the objects and identify the relationships between them.
	2. **Check the object relationships**: Once we have identified the objects, check the relationships between them. Look for strong references between the objects.
	3. **Use `weak` or `unowned` references**: If we find a strong reference between two objects that is causing the retain cycle, we can break the cycle by using a `weak` or `unowned` reference instead.
		
		```swift
		class MyViewController: UIViewController {
			var onComplete: (() -> Void)?

			func loadData() {
				onComplete = { [weak self] in
						self?.doSomething()
				}
			}
		}
  		```

	4. **Use a `weak` delegate**: If we have a delegate that is causing the retain cycle, we can make the delegate reference weak.

		```swift
		weak var delegate: SomeDelegate?
  		```
  
	5. **Use `deinit` to clean up**: Finally, we can use the `deinit` method to clean up any resources that might be causing the retain cycle.

		```swift
		deinit {
			print("MyViewController deinitialized")
		}
  		```
	</details>

- 🟧 [What is an efficient way to cache data in memory?](https://www.hackingwithswift.com/interview-questions/what-is-an-efficient-way-to-cache-data-in-memory)
	<details>
		<summary>Answer</summary>

	One efficient way to cache data in memory is to use `NSCache`, which is a class provided by Apple to manage a collection of key-value pairs in memory. `NSCache` is designed to automatically evict objects from the cache in response to memory pressure from the system, and it also provides thread-safe access to the cache.

	To use `NSCache`, we can create an instance of the class and set the maximum number of objects and the total cost limit of the cache. We can then add and retrieve objects from the cache using keys.

	Here's an example of using `NSCache` to cache image data:

	```swift
	class ImageCache {
		static let shared = ImageCache()
		
		private let cache = NSCache<NSString, NSData>()
		
		func getImageData(forKey key: String) -> Data? {
			return cache.object(forKey: key as NSString) as Data?
		}
		
		func setImageData(_ imageData: Data, forKey key: String) {
			cache.setObject(
				imageData as NSData, 
				forKey: key as NSString, 
				cost: imageData.count
			)
		}
	}
	```
	
	In this example, the `ImageCache` class uses a singleton pattern to provide a shared instance of the cache. The cache is defined as an instance of `NSCache<NSString, NSData>`, where the keys are `NSString` objects and the values are `NSData` objects. The `getImageData(forKey:)` method retrieves image data from the cache using a given key, and the `setImageData(_:forKey:)` method adds image data to the cache with a given key and cost.

	By using an `NSCache`, we can efficiently store and retrieve data in memory, which can be especially useful for performance-critical applications that need to access data quickly and frequently.
	</details>

- 🟧 [What steps do you take to identify and resolve battery life issues?](https://www.hackingwithswift.com/interview-questions/what-steps-do-you-take-to-identify-and-resolve-battery-life-issues)
	<details>
		<summary>Answer</summary>

	Here's how we can do this effectively:

	1. **Identify symptons or user reports**
		- High battery drain when the app is running or after using specific features.
		- Device feels hot
		- Users report performance or battery issues in reviews or feedback.

	2. **Profile with instruments**
		Xcode tools to use:
		- **Energy log**: Identifies which parts of the app are using the most energy. We have to identify spikes in energy use from CPU, GPU, networking, location and background activity.
		- **Time profiler**: Shows CPU usage over time and pinpoints CPU-intensive code paths.
		- **Network instruments**: Look for excessive or frequent requests.
		- **Leaks and allocations**: Check for memory leaks that may cause unintended background processing.

  	3. **Analyze common causes**
		- **Excessive background activity**: When the user isn't interacting with the app, it's important to minimize the amount of work that's being done. This includes things like suspending background tasks, stop GPS tracking if not needed, and using `beginBackgroundTask` along with `backgroundTaskIdentifier` for background tasks.
		- **High CPU/GPU usage**: Drawing can be a major drain on battery life, especially if the app is constantly redrawing the screen. To optimize drawing, consider using techniques such as layer masking, off-screen rendering, and Core Graphics to minimize the amount of drawing that needs to be done. In addition, heavy logic in main/UI thread can be battery-consuming, so it's important to offload work to background threads.
		- **Frequent network calls**: Network requests can also be a significant battery drain, especially if the app is making many small requests instead of a few larger ones. To optimize network performance, we need to consider batching requests whenever possible, and using techniques such as throttling, caching and compression to minimize the amount of data that needs to be transferred.
		- **Location services misuse**: Use significant location change or region monitoring when full GPS accuracy isn't needed. Also avoid using `startUpdatingLocation` when not needed.
		- **Timers or background tasks**: Uncontrolled `Timer` firing while app is idle or unmanaged `DispatchSource`, `RunLoop`, or `CADisplayLink` are common causes. To fix this, we need to invalidate timers when not in use and use system callbacks/events when possible.
		- **Push notifications**: Excessive silent push notifications wake up the app in the background, so we need to limit silent push usage; only use them when there's new data or real purpose.

	4. **Implement fixes and re-test**
		- Use instruments again after applying changes.
		- Compare battery impact before and after.
		- Test on real devices, not just the simulator.

	- **Extra tips**
		- Use `OSLog` for low-overhead logging when profiling energy or background activity.
		- Respect system throttling—iOS aggressively limits background tasks, timers, and networking in low-power mode.
		- Avoid keeping Bluetooth/Wi-Fi hardware active unnecessarily.
	</details>

- 🟧 [What steps do you take to identify and resolve crashes?](https://www.hackingwithswift.com/interview-questions/what-steps-do-you-take-to-identify-and-resolve-crashes)
	<details>
		<summary>Answer</summary>

	Identifying and resolving crashes is a crucial part of app development, and there are several steps that can be taken to accomplish this:

	1. **Capture the crash**: We can get crash reports from Xcode Organizer and Firebase Crashlytics. The key info to gather is the stack trace, the exception type, thread and symbol name, device OS version, device model, app version, and the reproduction steps (if known).
	2. **Analyze the stack trace**: Look at Thread 0 or the crashing thread and look for the details that pinpoint the part of the code that is crashing. Look for common patterns like force unwrap, array out-of-bounds, nil object access or retain cycles leading to `EXC_BAD_ACCESS`.
	3. **Reproduce the crash locally**: Try to determine what the user was doing when the crash occurred and replicate the conditions that led to the crash. Use breakpoints, `print()` / `debugPrint()`, or `NSLog()` to trace state, and `assert()` and `precondition()` to make sure that the data handled at a particular point in the app at runtime is correct. 
	4. **Fix the root cause**: Once we have identified the cause of the crash, change the code to prevent the crash from occurring in the future. This may involve refactoring the code, optimizing algorithms, or reducing memory usage.
	5. **Test the fix thoroughly**: After making changes to the code, test the fix to ensure that the crash no longer occurs. Use automated tests to verify the fix and perform manual testing to ensure that the app is functioning as expected.
	6. **Monitor post-release**: Re-deploy the app with the fix and monitor crash frequency in Crashlytics (or similar).
	</details>

- 🟥 [How does Swift handle memory management?](https://www.hackingwithswift.com/interview-questions/how-does-swift-handle-memory-management)
	<details>
		<summary>Answer</summary>

	Swift uses **Automatic Reference Counting (ARC)** for memory management. ARC automatically frees up memory that is no longer being used by keeping track of the number of references to each instance of an object. When the reference count of an object drops to zero, the object is deallocated. This is why structs and enums (value types) aren't involved—only classes use ARC.

	ARC works by inserting code at compile-time that automatically manages the reference counting of objects. Swift tracks strong references, which keep an object alive as long as there is **at least one strong reference to it**, and `weak` and `unowned` references, which allow references to an object without keeping it alive.

	Here's an example:

	```swift
	class Person {
		let name: String

		init(name: String) {
			self.name = name
			print("\(name) is being initialized")
		}

		deinit {
			print("\(name) is being deinitialized")
		}
	}

	func testARC() {
		// Declare three optional Person references
		var person1: Person?
		var person2: Person?
		var person3: Person?
			
		// ARC allocates memory and increases reference count to 1 for each new object
		person1 = Person(name: "Alice")   // Prints: "Alice is being initialized"
		person2 = Person(name: "Bob")     // Prints: "Bob is being initialized"
		person3 = Person(name: "Charlie") // Prints: "Charlie is being initialized"
			
		// Accessing the `name` property to demonstrate objects are alive
		person1?.name // "Alice"
		person2?.name // "Bob"
		person3?.name // "Charlie"
			
		// Set all references to nil
		// ARC decreases reference count for each Person instance to 0
		// Since no strong references remain, ARC deallocates the objects
		person1 = nil  // Prints: "Alice is being deinitialized"
		person2 = nil  // Prints: "Bob is being deinitialized"
		person3 = nil  // Prints: "Charlie is being deinitialized"
	}

	// Call the function — all ARC behavior happens within this scope
	testARC()
	```

  	Nonetheless, ARC alone isn't enough to avoid all memory issues—particularly **retain cycles**. To prevent these cycles from causing memory leaks, Swift provides the following language features to allow developers to create references between objects without increasing the reference count, which helps ARC determine when it's safe to deallocate memory:

	- **Capture lists in closures**: Since closures are reference types and can outlive the scope in which they're defined, they may retain `self`, creating a retain cycle if `self` also holds a strong reference to the closure (like storing it as a property). To solve this, Swift allows us to use a capture list to explicitly define how variables should be captured. Using `[weak self]` or `[unowned self]` in the closure's capture list ensures that the closure doesn't keep a strong reference to the surrounding object. This breaks the cycle and allows memory to be freed properly when it's no longer needed.

		```swift
		class ViewModel {
			var name: String = "Swift"
			var onNameUpdate: (() -> Void)?
	
			func setupClosure() {
				onNameUpdate = { [weak self] in
					guard let self else { return }
					print("Name is \(self.name)")
				}
			}
	
			deinit {
				print("ViewModel deinitialized")
			}
		}
		```

	- **`weak` reference**: It's used when one object refers to another, but shouldn't keep it alive. For example, in a delegate pattern, a child object might have a reference to its parent. Making this reference `weak` ensures the child doesn't keep the parent alive indefinitely. `weak` references must always be declared as optional, since the object they point to can be deallocated at any time—and when that happens, the reference is automatically set to `nil`. This prevents dangling pointers and makes the code safe.

		```swift
		class Owner {
			var pet: Pet?

			deinit {
				print("Owner deinitialized")
			}
		}

		class Pet {
			weak var owner: Owner?  // weak reference

			deinit {
				print("Pet deinitialized")
			}
		}

		var john: Owner? = Owner()
		var fluffy: Pet? = Pet()

		john?.pet = fluffy
		fluffy?.owner = john  // no strong reference cycle

		john = nil
		fluffy = nil

		// Output:
		// "Owner deinitialized"
		// "Pet deinitialized"
		```

	- **`unowned` reference**: It's similar to `weak`, but it's used when the referring object is guaranteed to outlive the object it references. Unlike `weak`, an `unowned` reference is non-optional. This is a performance optimization, but it comes with a trade-off: if the referenced object is deallocated and the `unowned` reference is accessed, the app will crash. Therefore, we should only use `unowned` when we're certain of the ownership relationship, such as in closures where the lifecycle is tightly controlled. It's safer to just use `weak` because `unowned` is rarely used and can potentially cause the app to crash.

		```swift
		class Customer {
			var creditCard: CreditCard?
	
			deinit {
				print("Customer deinitialized")
			}
		}
	
		class CreditCard {
			unowned var owner: Customer  // unowned reference
	
			init(owner: Customer) {
				self.owner = owner
			}
	
			deinit {
				print("CreditCard deinitialized")
			}
		}
	
		var john: Customer? = Customer()
		john?.creditCard = CreditCard(owner: john!)  // No cycle
	
		john = nil
	
		// ✅ Output:
		// "Customer deinitialized"
		// "CreditCard deinitialized"
		```

		Here's a table summing up the key differences between `weak` and `unowned`:
	
		<table>
			<tr>
				<th>FEATURE</th>
				<th><code>weak</code></th>
				<th><code>unowned</code></th>
			</tr>
			<tr>
				<td><strong>Optional</strong></td>
				<td>Yes (<code>var x: Type?</code>)</td>
				<td>No (<code>var x: Type</code>)</td>
			</tr>
			<tr>
				<td><strong>Becomes nil</strong></td>
				<td>Yes</td>
				<td>No</td>
			</tr>
			<tr>
				<td><strong>Safe access</strong></td>
				<td>Safe (optional binding)</td>
				<td>Crashes if accessed after dealloc</td>
			</tr>
			<tr>
				<td><strong>Use when</strong></td>
				<td>Referenced object may become <code>nil</code></td>
				<td>Object must outlive the reference</td>
			</tr>
		</table>

	Swift also has support for manual memory management using unsafe pointer types and memory allocation functions, but this is generally not recommended except for certain low-level system programming tasks.
	</details>

- 🟥 [How would you explain ARC to a new iOS developer?](https://www.hackingwithswift.com/interview-questions/how-would-you-explain-arc-to-a-new-ios-developer)
	<details>
		<summary>Answer</summary>

	**Automatic Reference Counting (ARC)** is a memory management system in Swift that automatically tracks and manages the allocation and deallocation of memory for an app's objects. ARC keeps track of how many references or pointers there are to an object in memory and automatically deallocates the object when there are no more references to it.

	In other words, when we create an object in Swift, ARC automatically assigns it a reference count of 1. Every time we create a new reference to the same object, for example by assigning it to a new variable or passing it as an argument to a function, the reference count is incremented by 1. When a reference to the object is removed, the reference count is decremented by 1. When the reference count reaches 0, ARC deallocates the object from memory.
	
	ARC makes memory management easier and less error-prone for developers because we don't have to manually keep track of how many references there are to an object and when to deallocate it.

	Here's an example:

	```swift
	class Person {
		let name: String
	
		init(name: String) {
			self.name = name
			print("\(name) is being initialized")
		}
	
		deinit {
			print("\(name) is being deinitialized")
		}
	}
	
	var person: Person? = Person(name: "Alice")  // ARC count = 1
	person = nil  // ARC count = 0 → deinit called, memory freed
 	```

	When the last reference is set to `nil`, ARC knows the object is no longer needed and deallocates it.

	Although ARC handles most memory management, it can't detect retain cycles, where two objects hold strong references to each other. This prevents ARC from deallocating them.

	Here's an example of a retain cycle:

	```swift
	class Owner {
		var pet: Pet?
	}
	
	class Pet {
		var owner: Owner?
	}
	```

	If the `owner` and `pet` strongly reference each other, they keep each other alive even after the rest of the code has finished using them. To resolve this issue, we can employ the `weak` or `unowned` reference types to break the cycle:

	```swift
	class Pet {
		weak var owner: Owner?  // now ARC won't retain the owner
	}
	```
	</details>

- 🟥 [What steps do you take to identify and resolve a memory leak?](https://www.hackingwithswift.com/interview-questions/what-steps-do-you-take-to-identify-and-resolve-a-memory-leak)
	<details>
		<summary>Answer</summary>

	Here are the steps I would take to identify and resolve a memory leak:

	1. **Recognize the symptons**: Look for signs like increasing memory over time, objects not getting deallocated, app slowdown or crashes due to memory pressure and `deinit` methods never being called.
	<br>

	2. **Use Xcode's memory debugging tools**:
		- **Memory graph debugger**: Run the app in debug mode and click on the **Memory graph** icon to open the memory graph debugger. There, we need to look for orphaned objects still in memory, reference cycles (shown as lines in the graph), and objects that should be deallocated but persist.
		- **Allocations & Leaks**: Open **Xcode > Services > Allocations & Leaks**. To start a session, run the app normally and look for retained objects that never go away. Use **Mark generation** to compare before/after memory states.
	<br>

	3. **Analyze the retention graph**: Use the memory graph to trace what's retaining the leaked object. Most leaks are caused by closures capturing `self` strongly, delegates not marked `weak`, and static singletons holding onto instances.
	<br>

	4. **Fix common memory leaks patterns**
		- **Closures**: They retain captured variables by default. Use capture lists:

			```swift
			// ⛔ Retain cycle
			self.callback = {
				self.doSomething()
			}
			
			// ✅ Fixed
			self.callback = { [weak self] in
				self?.doSomething()
			}
			```

		- **Delegates**: Always declare delegates as `weak` to avoid strong reference cycles:

			```swift
			weak var delegate: SomeDelegate?
			```

		- **Parent–child cycles**: For objects that reference each other (e.g., `Parent` and `Child`), make one reference `weak`:

			```swift
			class Child {
				weak var parent: Parent?
			}
			```
	<br>
   
	5. **Test the fix**: Re-run the memory graph and the Allocations & Leaks service to ensure that the objects are properly deallocated (`deinit` prints, gone from graph). Also, monitor the app during normal usage, especially screen transitions, to check that there are no memory leaks.
	<br>

	6. **Prevent future leaks**: Use `deinit` to track object lifecycles and be mindful of how closures and async code capture `self`. Also use `weak` or `unowned` as needed, as well as avoiding strong references in singletons or static variables unless necessary.
	</details>

- 🟥 [What steps do you take to identify and resolve performance issues?](https://www.hackingwithswift.com/interview-questions/what-steps-do-you-take-to-identify-and-resolve-performance-issues)
	<details>
		<summary>Answer</summary>

	Identifying and resolving performance issues can be a complex and iterative process. It involves a methodical approach combining profiling tools, code analysis, and targeted optimization. Here are some general steps that can be taken:

	1. **Recognize the symptons**: Look for issues like slow app launch, laggy scrolling ir UI stutters, delayed button taps or animations, and high CPU/GPU usage.
	<br>

	2. **Profile with Xcode instruments**: Launch Xcode instruments to collect real performance data. The key instruments are the following:
		- **Time Profiler**
			- Shows where the app spends time (CPU usage).
			- Identify heavy methods or long-running tasks.
		- **Core Animation**
			- Detects dropped frames or rendering bottlenecks.
			- Watch for spikes in layout, compositing, or offscreen rendering.
		- **Allocations & Leaks**
			- Detect excessive memory allocations.
			- Prevent memory churn or leaks causing slowdowns.
		- **Energy Log**
			- Detect high power usage from CPU, GPU, networking, or background work.
	<br>

	3. **Isolate the bottleneck**: Look for patterns in long function calls, synchronous work on the main thread (e.g., image decoding, JSON parsing), nested loops or large view hierarchies, and blocking network or file operations. Use Xcode's Debug Navigator (<kbd>⌘7</kbd>) to watch CPU, memory, and FPS live.
	<br>
 
	4. **Fix common performance issues**
	   	- **Heavy work on main thread**

			Move work off the main queue:
			
			```swift
			DispatchQueue.global().async {
				let result = performHeavyTask()
				DispatchQueue.main.async {
					self.updateUI(with: result)
				}
			}
	  		```
  
		- **Inefficient algorithms or loops**
			- Avoid `O(n^2)` loops.
			- Use sets/dictionaries instead of arrays for lookups.
			- Cache repeated calculations.
		
		- **UI overdraw or slow rendering**
			- Flatten view hierarchies.
			- Avoid unnecessary transparency, shadows, and masks.
			- Use rasterization carefully.
			- Profile with Core Animation.
		
		- **Image rocessing**
			- Resize or decode images off the main thread.
			- Use tools like `SDWebImage`, `ImageIO`, or Core Graphics smartly.
			- Use `NSCache` for in-memory caching.
		
		- **Networking**
			- Avoid redundant requests or polling.
			- Use background fetch or batching.
			- Cache responses where appropriate.
	<br>

	5. **Test and iterate**: Once we have made changes to our code to improve performance, test the app again using profiling tools to see if the changes have had the desired effect. Iterate on the process until we are satisfied with the app's performance.
	<br>

	6. **Consider hardware limitations**: Remember that different devices have different hardware capabilities, and what works well on one device may not work as well on another. Be sure to test our app on a range of devices to ensure that it performs well on all of them.
	</details>

<p align="right">(<a href="#top">back to top</a>)</p>

## Security

- 🟩 [How much experience do you have using Face ID or Touch ID? Can you give examples?](https://www.hackingwithswift.com/interview-questions/how-much-experience-do-you-have-using-face-id-or-touch-id-can-you-give-examples)
	<details>
		<summary>Answer</summary>

	The answer depends on your experience with Face ID or Touch ID. Here's how I would approach it:

	>I have used them as an alternative login method for applications that stored sensitive information, such as bank transactions and stock positions. I have also used them in an application that stored sensitive information in the keychain, which users could access by logging in with Face ID or Touch ID.
	</details>

- 🟩 [How would you explain App Transport Security to a new iOS developer?](https://www.hackingwithswift.com/interview-questions/how-would-you-explain-app-transport-security-to-a-new-ios-developer)
	<details>
		<summary>Answer</summary>

	App Transport Security (ATS) is a security feature that was introduced in iOS 9 and later versions of iOS. It is enabled by default in all apps, and it blocks any non-secure (HTTP) connections by default to ensure that your app only communicates with servers using secure HTTPS connections, which encrypts the data sent.

	To enable a connection that is not compliant with ATS, we must configure our app's `Info.plist` file to include an exception for that domain, such as the following:

	```xml
	<key>NSAppTransportSecurity</key>
	<dict>
		<key>NSAllowsArbitraryLoads</key> 
		<false/>
		<key>NSExceptionDomains</key>
		<dict>
			<key>example.com</key> <!--Include your domain at this line -->
			<dict>
				<key>NSIncludesSubdomains</key>
				<true/>
				<key>NSTemporaryExceptionAllowsInsecureHTTPLoads</key>
				<true/>
				<key>NSTemporaryExceptionMinimumTLSVersion</key>
				<string>TLSv1.1</string>
			</dict>
		</dict>
	</dict>
 	```
 	>Code taken from [this Stackoverflow post](https://stackoverflow.com/a/32560433/15675885).
	</details>

- 🟩 [What experience do you have of using the keychain?](https://www.hackingwithswift.com/interview-questions/what-experience-do-you-have-of-using-the-keychain)
	<details>
		<summary>Answer</summary>

	The answer depends on your experience with the keychain. Here's how I would approach it:
	
	>I have used the iOS Keychain to securely store an retrieve sensitive data, such as authentication tokens or user credentials. I ensure that the keychain items use appropriate accessibility levels depending on the use case—for example, `.whenUnlocked` for tokens that should only be available when the device is unlocked, or `.whenPasscodeSetThisDeviceOnly` with `.userPresence` to add biometric protection via Face ID or Touch ID. It's very convenient to use an access control mechanism along with the keychain, such as requiring a passcode or biometric authentication, to ensure that only authorized users can access the data.
	</details>

- 🟧 [How would you calculate the secure hash value for some data?](https://www.hackingwithswift.com/interview-questions/how-would-you-calculate-the-secure-hash-value-for-some-data)
	<details>
		<summary>Answer</summary>

	We can calculate the secure hash value for some data using CryptoKit's `SHA256` algorithm as follows:

	```swift
	import CryptoKit

	// Create a message to hash
	let message = "Hello, world!".data(using: .utf8)!
	
	// Hash the message using SHA256
	let digest = SHA256.hash(data: message)
	
	// Convert the digest to a hex string
	let digestHex = digest.map { String(format: "%02hhx", $0) }.joined()
	print(digestHex)
	```
	
	In this example, we create a message to hash, convert it to a `Data` object, and then use the `SHA256` hash function from the `CryptoKit` framework to compute the digest. Finally, we convert the digest to a hex string for display.

	Note that this example uses `SHA256` for illustrative purposes, but we can use other secure hash functions provided by the `CryptoKit` framework, such as `SHA512`, `SHA384`, `SHA224`, `SHA1`, `MD5`, etc.
	</details>

<p align="right">(<a href="#top">back to top</a>)</p>

## Swift

- 🟩 [How would you compare two tuples to ensure their values are identical?](https://www.hackingwithswift.com/interview-questions/how-would-you-compare-two-tuples-to-ensure-their-values-are-identical)
	<details>
		<summary>Answer</summary>
	 
	In Swift, we can compare two tuples to ensure their values are identical using the `==` operator, **as long as the types inside the tuples conform to `Equatable`**. The `==` operator returns `true` if the corresponding elements of the tuples are equal, and `false` otherwise.

	Here's an example: 
	
	```swift
	let tuple1 = (1, "hello")
	let tuple2 = (1, "hello")
	let tuple3 = (2, "world")

	if tuple1 == tuple2 {
		print("tuple1 and tuple2 are identical")  // ✅ printed
	} else {
		print("tuple1 and tuple2 are different")  // ❌ not printed
	}

	if tuple1 == tuple3 {
		print("tuple1 and tuple3 are identical")  // ❌ not printed
	} else {
		print("tuple1 and tuple3 are different")  // ✅ printed
	}
	```
	</details>

- 🟩 [How would you explain operator overloading to a junior developer?](https://www.hackingwithswift.com/interview-questions/how-would-you-explain-operator-overloading-to-a-junior-developer)
	<details>
		<summary>Answer</summary>
		
	Operator overloading allows us to define our own implementation for existing operators or even create new operators. This can be very useful when working with custom types, as it allows us to define how those types should behave with the standard operators.

	To overload an operator in Swift, we need to define a function that implements the behavior of that operator. The function must be marked with the `static` or `prefix`, `infix`, or `postfix` keyword, depending on the type of operator we want to overload. For example, to overload the `+` operator for a custom class `MyClass`, we could define a function like this:
	
	```swift
	static func +(lhs: MyClass, rhs: MyClass) -> MyClass {
		// implementation of the + operator for MyClass
	}
	```

	In this function, `lhs` and `rhs` represent the left-hand side and right-hand side operands of the `+` operator, respectively. The function should return the result of the operation, which should also be of type `MyClass`.

	Once we have defined the function, we can use the + operator with instances of our MyClass type just like we would with the built-in types.

	Here's an example of how we could use the `+` operator with a custom class `Vector2D` that represents a 2D vector:
	
	```swift
	struct Vector2D {
		var x: Double
		var y: Double

	 	// Define the + operator for Vector2D
		static func +(lhs: Vector2D, rhs: Vector2D) -> Vector2D {
			return Vector2D(x: lhs.x + rhs.x, y: lhs.y + rhs.y)
		}
	}

	let v1 = Vector2D(x: 1.0, y: 2.0)
	let v2 = Vector2D(x: 3.0, y: 4.0)
	let result = v1 + v2  // Vector(x: 4.0, y: 6,0)
	```
	 </details>
	 
- 🟩 [How would you explain protocols to a new Swift developer?](https://www.hackingwithswift.com/interview-questions/how-would-you-explain-protocols-to-a-new-swift-developer)
	<details>
		<summary>Answer</summary>
		
	In Swift, a protocol is a blueprint of methods, properties, and other requirements that a class, structure, or enumeration can conform to. Essentially, a protocol defines a set of rules or guidelines that a type must follow in order to implement that protocol.

	To establish a real-world analogy to protocols, think of them as a power plug interface. The wall outlet defines the shape (contract), and any device that wants to plug in (conform to the protocol) has to match that shape. However, the function of the device is irrelevant as long as it plugs in the same way.
		
	Protocols are similar to interfaces in other programming languages, but with additional capabilities. They allow us to define a set of methods and properties that a type must implement, but they can also provide default implementations for some methods and allow us to add constraints on associated types.

	Here's an example of a simple protocol in Swift:

	```swift
	protocol Drawable {
		func draw()
	}
	```
		
	In this example, we define a protocol called `Drawable` that requires any conforming type to implement a method called `draw()`. The implementation of the `draw()` method is left up to the conforming type.

	To make a class, struct, or enum conform to the `Drawable` protocol, we simply need to add the protocol name after the type name, separated by a colon. For example:
		
	```swift
	class Circle: Drawable {
		func draw() {
			// implementation of the draw() method for Circle
		}
	}
	```
		
	In this example, we define a class called `Circle` that conforms to the `Drawable` protocol by implementing the `draw()` method.

	We can also use protocols as types, which allows us to pass any object that conforms to a specific protocol as a parameter or store it as a property. For example:

	```swift
	func drawObject(object: Drawable) {
		object.draw()
	}
	```
		
	In this example, we define a function called `drawObject()` that takes an object conforming to the `Drawable` protocol as a parameter. The function then calls the `draw()` method on the object, which is guaranteed to be implemented by any object conforming to the `Drawable` protocol.
	</details>

- 🟩 [In which situations do Swift functions not need a `return` keyword?](https://www.hackingwithswift.com/interview-questions/in-which-situations-do-swift-functions-not-need-a-return-keyword)
	<details>
		<summary>Answer</summary>

	In Swift, functions may not need a `return` keyword in two main situations:
			
	1. **Void functions**: If a function doesn't need to return a value, we can declare it as a "void" function by specifying the return type as `Void` or `()` (an empty tuple). In this case, we don't need to use the return keyword at all. For example:

		```swift 
		func printMessage() -> Void {
			print("Hello, world!")
		}

		func doSomething() -> () {
			// do something
		}
		```

		In both cases, we can omit the `-> Void` or `-> ()` part and simply declare the function as:

		```swift
		func printMessage() {
			print("Hello, world!")
		}

		func doSomething() {
			// do something
		}
		```
	
	2. **Implicit returns**: If a function consists of a single expression, we can use an "implicit return" and omit the return keyword. The expression's value will be automatically returned as the result of the function. For example:

		```swift
		func square(_ x: Int) -> Int {
			return x * x
		}
	
		func sayHello() -> String {
			return  "Hello, world!"
		}
		```

		In both cases, we can omit the `-> Int` or `-> String` part and simply declare the function as:
	
		```swift
		func square(_ x: Int) -> Int {
			x * x
		}
	
		func sayHello() -> String {
			"Hello, world!"
		}
		```
	
		Note that implicit returns can only be used for single-expression functions. If a function has multiple expressions—more than one line—, we must use the `return` keyword to explicitly return a value.
	</details>

- 🟩 [What are property observers?](https://www.hackingwithswift.com/interview-questions/what-are-property-observers)
	<details>
		<summary>Answer</summary>

	Property observers in Swift let us monitor and respond to changes in a property's value—_before or after_ it's set. They're useful for triggering some side-effect when a property changes, validating or log value changes, and updating dependent data or UI.
	
	There are two types of property observers:
	
	- `willSet`: Called **just before** the new value is set. It receives the new value as a parameter, which we can use to perform some action before the value is set.
	- `didSet`: Called **immediately after** the new value is set. It receives the old value as a parameter, which we can use to perform some action after the value has been set.
	<br />

	Here's an example:

	```swift
	class Temperature {
		var celsius: Double = 0.0 {
			willSet(newCelsiusValue) {
				print("About to set temperature to \(newCelsiusValue) degrees Celsius")
			}
			didSet(oldCelsiusValue) {
				print("Temperature was set from \(oldCelsiusValue) to \(celsius) degrees Celsius")
			}
		}
	}

	let temp = Temperature()

	temp.celsius = 25.0
	// About to set temperature to 25.0 degrees Celsius
	// Temperature was set from 0.0 to 25.0 degrees Celsius

	temp.celsius = 30.0
	// About to set temperature to 30.0 degrees Celsius
	// Temperature was set from 25.0 to 30.0 degrees Celsius
	```

	Note that property observer **do not trigger** during initialization. Also, we **cannot use observers** on computed properties (those with `get`/`set`).
	</details>

- 🟩 [What are raw strings?](https://www.hackingwithswift.com/interview-questions/what-are-raw-strings)
	<details>
		<summary>Answer</summary>

	Raw strings in Swift are string literals that allow us to include characters like backslashes (`\`) and quotes (`"`) **without needing to escape them**. They're especially useful when working with **regex**, **file paths**, or **complex strings** where escaping would make the code hard to read.

	Normally, we have to escape certain characters in strings:

	```swift
	let text = "This is a \"quoted\" word and a backslash: \\"
	```

	With raw strings, we can write the same thing **without escaping**:

	```swift
	let rawText = #"This is a "quoted" word and a backslash: \"#
	```

	Raw strings are wrapped in **`#"` and `"#`** instead of just `"`.

	We can even use **multiple `#` signs** if the string includes `#` characters:

	```swift
	let tricky = ##"String with a # and a quote: "#cool""##
	```

	To include interpolated values in a raw string, **match the number of `#` signs**:

	```swift
	let name = "Alice"
	let greeting = #"Hello, \#(name)!"#  // Outputs: Hello, Alice!
	```

	It's better to use raw strings:
	- Regex patterns (e.g. `"\\d{3}" → #"\d{3}"#`).
	- File paths with backslashes.
	- Copy-pasting JSON/XML or other code into strings.
	- Reducing backslash overload in complex literals.
	</details>

- 🟩 [What does the `#error` compiler directive do?](https://www.hackingwithswift.com/interview-questions/what-does-the-error-compiler-directive-do)
	<details>
		<summary>Answer</summary>
	
	The `#error` compiler directive in Swift is used to generate a compile-time error message. It is used to indicate that a particular block of code should not be compiled, and to provide an error message to the developer explaining why.

	The syntax of the `#error` directive is as follows:

	```swift
	#error("Error message")
	```
	
	Here's an example of how we might use the `#error` directive in Swift:

	```swift
	#if os(macOS)
	// Do some macOS-specific stuff
	#elseif os(iOS)
	// Do some iOS-specific stuff
	#else
	#error("Unsupported platform")
	#endif
	```
	
	In this example, the code checks the operating system using the `os` compiler directive. If the OS is macOS or iOS, it executes the appropriate code. If the OS is neither of those, it generates a compile-time error with the message `Unsupported platform`.

	Using the `#error` directive can be helpful in marking unfinished features during development, preventing code from compiling in unsupported conditions, flagging incomplete platform-specific branches, and enforcing checks during manual configuration.
	</details>

- 🟩 [What does the `#if swift` syntax do?](https://www.hackingwithswift.com/interview-questions/what-does-the-if-swift-syntax-do)
	<details>
		<summary>Answer</summary>

	The `#if swift` syntax is a compiler directive in Swift that allows conditional compilation based on the version of the Swift language being used.

	This syntax is typically used to ensure compatibility with different versions of the Swift language, and to enable or disable certain blocks of code depending on the version being used.

	Here's an example of how we might use the `#if` swift directive:

	```swift
	#if swift(>=5.0)
	// Code that is only available in Swift 5.0 or later
	#elseif swift(>=4.0)
	// Code that is only available in Swift 4.0 or later
	#else
	// Code that is only available in earlier versions of Swift
	#endif
	```

	In this example, the `#if swift` directive is used to conditionally compile code based on the version of Swift being used. If the version is 5.0 or later, the first block of code will be executed. If the version is between 4.0 and 5.0, the second block of code will be executed. If the version is earlier than 4.0, the third block of code will be executed.

	The `#if swift` directive is a powerful tool for ensuring that our code is compatible with multiple versions of the Swift language, and for enabling or disabling certain features based on the version being used.
	</details>

- 🟩 [What does the `assert()` function do?](https://www.hackingwithswift.com/interview-questions/what-does-the-assert-function-do)
	<details>
		<summary>Answer</summary>

	In Swift, the `assert()` function is used to assert that a certain condition is `true` during runtime. If the condition evaluates to `false`, an assertion failure will occur, causing the program to terminate immediately.

	The syntax for the `assert()` function is as follows:

	```swift
	assert(_:_:file:line:)
	```
	
	The first parameter is the condition to test, the second is an optional message to display if the assertion fails, and the last two parameters specify the file and line number where the assertion occurred.

	Here's an example of how we might use the `assert()` function:

	```swift
	func divide(_ a: Int, by b: Int) -> Int {
		assert(b != 0, "Cannot divide by zero")
		return a / b
	}

	let result = divide(10, by: 5)  // Returns 2
	let invalidResult = divide(10, by: 0)  // ❌ Assertion failure: "Cannot divide by zero"
	```

	In this example, the `assert()` function is used to ensure that the divisor (`b`) is not zero when dividing `a` by `b`. If the divisor is zero, the assertion fails with the message "Cannot divide by zero", and the program terminates immediately.

	The `assert()` function in Swift is used to **check assumptions during development**. If the condition we pass to `assert()` evaluates to `false`, it **stops the program at runtime** and prints an error message—but only in **debug builds**.
	</details>

- 🟩 [What does the `canImport()` compiler condition do?](https://www.hackingwithswift.com/interview-questions/what-does-the-canimport-compiler-condition-do)
	<details>
		<summary>Answer</summary>

	The `canImport()` compiler condition in Swift is used to check at **compile time** whether a module (like a framework or library) is available to import on the current platform or build configuration.

	The syntax for the `canImport()` condition is as follows:

	```swift
	#if canImport(ModuleName)
	import ModuleName
	#endif
	```
	
	If the specified module can be imported, the code inside the block is compiled. If it's not available, the block is skipped and no compile error occurs.

	Here's an example of how we might use the `canImport()` condition:

	```swift
	#if canImport(UIKit)
	import UIKit
	#elseif canImport(AppKit)
	import AppKit
	#endif
	```
	
	This is useful when writing cross-platform Swift code (e.g., for iOS, macOS, Linux), where some modules exist only on certain platforms.

	Bear in mind that if we try to import a module without wrapping it in `#if canImport`, and the module doesn't exist, the code will fail to compile.
	</details>

- 🟩 [What does the `CaseIterable` protocol do?](https://www.hackingwithswift.com/interview-questions/what-does-the-caseiterable-protocol-do)
	<details>
		<summary>Answer</summary>

	`CaseIterable` protocol is a Swift protocol used to provide a collection of all the cases of an enumeration type.

	By conforming an enumeration to `CaseIterable`, the enumeration automatically gains a static `allCases` property, which is an array containing all the enumeration's cases. The cases in the array are ordered in the order in which they were declared in the enumeration definition.

	Here's an example of an enumeration that conforms to `CaseIterable`:
	
	```swift
	enum CompassDirection: CaseIterable {
		case north, south, east, west
	}

	// Access all the cases using the allCases property
	for direction in CompassDirection.allCases {
		print(direction)
	}
	```
	
	In this example, the `CompassDirection` enumeration is defined with four cases: `north`, `south`, `east`, and `west`. By conforming the enumeration to `CaseIterable`, the `allCases` property is automatically generated. The `for` loop at the bottom of the example uses this property to iterate over all the enumeration's cases and print them to the console.

	`CaseIterable` is useful for:
	- Populating UI components (e.g., `UIPickerView`, `SegmentedControl`).
	- Displaying all options in a `Form` or `List` (especially in SwiftUI).
	- Building settings screens, filters, or test cases.
	- Serializing/deserializing enums.

	Note that `CaseIterable` only works with enums **without associated values**. For enums with associated values, we must implement `allCases` manually:

	```swift
	enum Status {
		case success(code: Int)
		case failure(reason: String)
		// ❌ Not CaseIterable by default
	}
 	```
	</details>

- 🟩 [What does the `final` keyword do, and why would you want to use it?](https://www.hackingwithswift.com/interview-questions/what-does-the-final-keyword-do-and-why-would-you-want-to-use-it)
	<details>
		<summary>Answer</summary>

	In Swift, the `final` keyword indicates that a class, property, or method cannot be subclassed, overridden, or modified by other classes or methods through inheritance.

	Here's an example:

	```swift
	final class MyClass {
		// This class cannot be subclassed
	}

	class BaseClass {
		// This method can be overridden in a subclass
		func myMethod() {
			// ...
		}

		// This method cannot be overridden in a subclass
		final func myFinalMethod() {
			// ...
		}
	}
	```
	
	The main reason to use the `final` keyword is to prevent other developers from modifying our code in ways that could cause bugs or introduce unexpected behavior. By marking a class, property, or method as `final`, we are ensuring that its behavior will not change unexpectedly in subclasses or extensions. This can be particularly important in larger codebases where multiple developers are working on the same project.

	In addition to providing safety, marking classes, methods, and properties as `final` can also improve performance. When the Swift compiler sees that a class or method is `final`, it can make certain optimizations that would not be possible otherwise. This can result in faster code execution and lower memory usage.
	</details>

- 🟩 [What does the nil coalescing operator do?](https://www.hackingwithswift.com/interview-questions/what-does-the-nil-coalescing-operator-do)
	<details>
		<summary>Answer</summary>

	The nil coalescing operator (`??`) in Swift provides a default value when an optional is nil. It's a concise way to safely unwrap an optional with a fallback.

	Here's the syntax for the nil coalescing operator:

	```swift
	let result = optionalValue ?? defaultValue
	```
	
	- If `optionalValue` is non-nil, it's unwrapped and returned.
	- If `optionalValue` is nil, `defaultValue` is returned instead.

	Here's an example:

	```swift
	let username: String? = nil
	let displayName = username ?? "Guest"
	print(displayName)  // Output: Guest
	```
	
	If `username` had a value, like `"Alice"`, `displayName` would be `"Alice"` instead.
	</details>

- 🟩 [What is the difference between `if let` and `guard let`?](https://www.hackingwithswift.com/interview-questions/what-is-the-difference-between-if-let-and-guard-let)
	<details>
		<summary>Answer</summary>

	Both `if let` and `guard let` are used in Swift to safely unwrap optional values, but they differ in how they handle execution flow.

	`if let` is used to conditionally bind the unwrapped optional to a new non-optional variable. If the optional has a value, the condition evaluates to `true`, and the block of code inside the `if` statement is executed. If the optional is `nil`, the condition evaluates to `false`, and the code inside the `if` statement is skipped.

	Here's an example using `if let`:

	```swift
	if let name = optionalName {
		print("Hello, \(name)!")
	} else {
		print("Hello, stranger!")
	}
	```
	
	- If `optionalName` has a value, it's unwrapped into `name`.
	- If it's `nil`, the `else` block runs.
	- The unwrapped value (`name`) is only available inside the `if` block.
	<br>

	`guard let`, on the other hand, is used to ensure that an optional has a value. If the optional has a value, the unwrapped value is assigned to a new non-optional variable, and the execution continues after the `guard` statement. If the optional is `nil`, the `guard` statement fails, and the execution branches to the `else` statement, which typically contains a `return`, `break`, or `throw` statement.

	Here's an example using `guard let`:

	```swift
	func greet(_ optionalName: String?) {
		guard let name = optionalName else {
			print("Please provide a name.")
			return
		}
		print("Hello, \(name)!")
	}
	
	greet(nil)  // prints "Please provide a name."
	greet("John")  // prints "Hello, John!"
	```

	- If `name` is `nil`, the `else` block must exit (using `return`, `break`, `continue`, or `fatalError`).
	- If it's non-nil, execution continues and `name` is available after the `guard` block.  
	<br>

	In summary, `if let` is used to conditionally execute code based on the presence of an optional value, while `guard let` is used to ensure that an optional has a value and to exit early from a scope if it doesn't.
	</details>

- 🟩 [What is the difference between `try`, `try?`, and `try!` in Swift?](https://www.hackingwithswift.com/interview-questions/what-is-the-difference-between-try-try-and-try-in-swift)
	<details>
		<summary>Answer</summary>

	In Swift, `try`, `try?`, and `try!` are used to handle errors that can be thrown by a function or method call that is marked as throws. Here are the differences between them:

	1. `try`: This is used when we want to execute a throwing function or method and handle the errors that can be thrown using a `do-catch` block. The `try` keyword is placed before the function or method call that can throw an error. It's the safest and most flexible option.
		```swift
		do {
			let result = try someThrowingFunction()
			print(result)
		} catch {
			print("Error: \(error)")
		}
  		```

	2. `try?`: This is used when we want to call a throwing function or method and convert any error that is thrown into an optional value. If the function or method call returns a value, it will be wrapped in an optional. If an error is thrown, the result will be `nil`.
		```swift
		let result = try? someThrowingFunction()
  		```

	3. `try!`: This is used when we are absolutely certain that the function or method call will not throw an error, and we want to force the result to be unwrapped. If an error is thrown, our program will crash with a runtime error.
		```swift
		let result = try! someThrowingFunction()
  		```
	<br />

	In general, it is recommended to use `try` and handle errors using a `do-catch` block whenever possible, as this provides better error handling and makes our code more robust. `try?` and `try!` should be used sparingly, and only when we are sure that the function or method call will never fail.
	</details>

- 🟩 [What problem does optional chaining solve?](https://www.hackingwithswift.com/interview-questions/what-problem-does-optional-chaining-solve)
	<details>
		<summary>Answer</summary>

	Optional chaining in Swift solves the problem of safely accessing properties, methods, or subscripts on optional values without unwrapping them manually. It helps us avoid deeply nested `if let` or `guard let` statements and makes code cleaner, safer, and more concise.

	Let’s say we have a chain of objects, and one or more links might be `nil`:

  	```swift
	person.address?.city?.name
   	```

	Without optional chaining, we'd need to unwrap each step:

   	```swift
	if let address = person.address {
		if let city = address.city {
			print(city.name)
		}
	}
	```

	This gets tedious and cluttered, especially as the chain gets longer. However, optional chaining lets us attempt the entire chain in one expression:

	```swift
	if let cityName = person.address?.city?.name {
		print(cityName)
	}
 	```

 	If any link in the chain is `nil`, the whole expression becomes `nil` without crashing.

  	Optional chaining can also be used with method calls and subscripts:

	```swift
	person.address?.printLabel()
 	let street = person.address?.streets?[0]
 	```
	</details>

- 🟩 [What's the difference between `String?` and `String!` in Swift?](https://www.hackingwithswift.com/interview-questions/whats-the-difference-between-string-and-string-in-swift)
	<details>
		<summary>Answer</summary>
	
	In Swift, `String?` and `String!` are both optional types, but they differ in how they are unwrapped.
	
	- `String?`
 		```swift
		 var name: String? = "Alice"
		 print(name)  // Prints: Optional("Alice")
		
		 var name2: String? = nil
		 print(name2)  // Prints: nil
		```

		- Can be either a `String` or `nil`.
		- Must be safely unwrapped using optional binding (`if let`, `guard let`), optional chaining, or the `??` operator.
		- Preferred for safe, defensive programming.

	- `String!`
		```swift
		var name: String! = "Alice"
		print(name!)  // ✅ Prints: "Alice"
  
		var name2: String! = nil
		print(name2!)  // ❌ Runtime crash: unexpectedly found nil while unwrapping
		```

		- Also can be a `String` or `nil`.
		- Assumed to always have a value, so we can use it without unwrapping.
		- Crashes at runtime if it's `nil` and accessed.
	</details>

- 🟩 [When would you use the `guard` keyword in Swift?](https://www.hackingwithswift.com/interview-questions/when-would-you-use-the-guard-keyword-in-swift)
	<details>
		<summary>Answer</summary>

	We would use the `guard` keyword in Swift to to check a condition early in a function or block and exit immediately if it fails. It's ideal for early exits, also known as the "early return" pattern, which helps keep the code clean, readable, and flat (avoiding nested ifs).

	The `guard` statement is similar to the `if` statement, but it is used to check if a condition is `false` or if a value is `nil`. The key difference is that when the condition fails, the `guard` statement requires us to exit the current scope, either by throwing an error, or using `return`, `continue`, `break`, or `fatalError()`. This ensures that we handle the error condition as early as possible and avoid nested conditional statements.

	Here's an example of using `guard` to check if a string is not `nil` and not empty, and then perform some operation on it:

	```swift
	func greet(_ name: String?) {
		guard let name = name else {
			print("No name provided")
			return
		}
		print("Hello, \(name)")
	}
	```
	
	If `name` is `nil`, it prints a message and returns early. If not, it safely unwraps `name` for use afterward—no need for nesting.

	Overall, `guard` improves clarity by focusing on what must be `true`, not how to handle `false`.
	</details>

- 🟧 [Apart from the built-in ones, can you give an example of property wrappers?](https://www.hackingwithswift.com/interview-questions/apart-from-the-built-in-ones-can-you-give-an-example-of-property-wrappers)
	<details>
		<summary>Answer</summary>

	In Swift, we can create custom property wrappers to encapsulate common behaviors—such as validation, formatting, or storage—and apply them to properties in a reusable way.

	Here's a simple, custom property wrapper example: a wrapper that caps a value to a maximum limit.

	```swift
	@propertyWrapper
	struct Clamped<Value: Comparable> {
		var value: Value
		let range: ClosedRange<Value>
	
		init(wrappedValue: Value, range: ClosedRange<Value>) {
			self.value = min(max(wrappedValue, range.lowerBound), range.upperBound)
			self.range = range
		}
	
		var wrappedValue: Value {
			get { value }
			set { value = min(max(newValue, range.lowerBound), range.upperBound) }
		}
	}
	```

	Here's an example of how to use the `Clamped` property wrapper:

	```swift
	struct Player {
		@Clamped(0...100) var health: Int = 120
		@Clamped(0...10) var lives: Int = 3
	}
	
	var player = Player()
	print(player.health)  // 100 — clamped to max
	player.health = -50
	print(player.health)  // 0 — clamped to min
 	```
	
	When a value using the `@Clamped` property wrapper is set, it's automatically restricted to a range. There's no need to manually enforce the range each time the value changes.

	Custom property wrappers are useful for encapsulating common logic, keeping structs/classes clean, and improve readabililty and intent clarity.
	</details>

- 🟧 [Can you give useful examples of enum associated values?](https://www.hackingwithswift.com/interview-questions/can-you-give-useful-examples-of-enum-associated-values)
	<details>
		<summary>Answer</summary>

	Enums with associated values in Swift let us store extra, type-specific data alongside each case. This makes enums much more powerful than just labels—they can represent rich, structured data in a type-safe way.

	Here are some usage examples:

	1. **Payment methods**: When building a checkout system, users may pay in different ways. With this enum, each payment method can carry the relevant data needed to process that specific method: card details for credit cards, a token for Apple Pay, and no data for cash. This allows the payment processing logic to pattern-match on the payment type and handle each accordingly, without risking mismatched data.
	
		```swift
		enum PaymentMethod {
			case creditCard(number: String, expiry: String)
			case applePay(token: String)
			case cash
		}
		```

	2. **Representing API responses**: This enum models the two possible outcomes of an API call: success or failure. When the call succeeds, we often get a `Data` object back, which can then be decoded into usable models. If the call fails, an `Error` object is typically returned, which we can use for debugging or displaying a user-friendly message.

		This design is powerful because it keeps both outcomes together in a type-safe way and forces us to handle both scenarios explicitly via a `switch`.

		```swift
		enum APIResponse {
			case success(data: Data)
			case failure(error: Error)
		}
		```

	3. **Navigation**: enums with associated values can be used to model navigation in an iOS app. For example, we could define an enum with associated values to represent different screens in our app. Here's an example:

		```swift
		enum Screen {
			case home
			case profile(username: String)
			case settings(isLoggedIn: Bool)
		}
		```

		This `enum` allows us to represent different screens in our app, such as the home screen, the user profile screen (with a `username` associated value), or the settings screen (with an `isLoggedIn` associated value). We can use this `enum` to navigate between screens in our app.

	4. **Coordinates with units**: This is useful when we're dealing with location data that could be in two formats: actual GPS coordinates or a plain-text address. Using an enum with associated values ensures that each value is tied to its respective format, eliminating the need to track whether a location is coordinate- or address-based using separate flags or logic.

		It improves code clarity and reduces the chances of misinterpreting the location data.
	
		```swift
		enum Coordinate {
			case gps(latitude: Double, longitude: Double)
			case address(String)
		}
	 	```

 	5. **Color model**: Colors can be defined in multiple formats, with RGB and HEX being the most common. This enum encapsulates that concept, allowing us to work with either type while keeping them neatly organized. We may add `.hsl(hue:saturation:lightness:)` or `.named(String)` for other cases later on.

		Using associated values like this is much cleaner than having a color model that stores all possible formats at once and requires complex logic to determine which one is in use.

		```swift
		enum Color {
			case rgb(red: Int, green: Int, blue: Int)
			case hex(String)
		}
	 	```
	</details>

- 🟧 [How would you explain closures to a new Swift developer?](https://www.hackingwithswift.com/interview-questions/how-would-you-explain-closures-to-a-new-swift-developer)
	<details>
		<summary>Answer</summary>

	Closures in Swift are self-contained blocks of code that can be passed around and used in our code just like any other variable or constant. Think of them like functions that we can define inline and then use them whenever and wherever we need them. They are useful because they can capture and store references to any constants and variables from the surrounding context in which they are defined. This makes them particularly powerful for tasks such as sorting and filtering arrays, as well as handling asynchronous tasks and callbacks.

	To define a closure in Swift, we use curly braces `{}` and the `in` keyword to separate the closure's parameters and return type from its body. Here's a simple example:

	```swift
	let add = { (a: Int, b: Int) -> Int in
		return a + b
	}
	
	let result = add(3, 5)  // result is 8
	```
	
	This is a closure that behaves like a function; it takes two parameters and returns an integer.

	Here's another example with different syntax:

	```swift
	let names = ["Charlie", "Alice", "Bob"]
	
	let sorted = names.sorted { $0 < $1 }  // Closure decides how to sort
	print(sorted)  // ["Alice", "Bob", "Charlie"]
	```
 
	The `{ $0 < $1 }` part is a closure that tells sorted how to compare two values.

  	A closure has this basic structure:

  	```swift
	{ (parameters) -> ReturnType in
		// body
	}
	```

	But Swift allows to omit parts when they're obvious:
	- Omit types (they're inferred).
	- Omit `return` if it's a single expression.
	- Use shorthand arguments like `$0`, `$1`, etc.

	We can also pass closures as parameters:

	```swift
	func doSomething(action: () -> Void) {
		print("Before action")
		action()
		print("After action")
	}
	
	doSomething {
		print("Doing the action")
	}
	```

	Output:

	```
	Before action
	Doing the action
	After action
	```

	This is the foundation for things like completion handlers, animations, and event callbacks.
	</details>

- 🟧 [What are generics and why are they useful?](https://www.hackingwithswift.com/interview-questions/what-are-generics-and-why-are-they-useful)
	<details>
		<summary>Answer</summary>
	
	Generics allow us to write code like functions, structs, classes, or enums that work with placeholder types, which are specified when the code is used. They let us write reusable code that can work with any type, rather than being limited to a specific one. They're a fundamental feature for building type-safe abstractions.

	To use them in Swift, we need to enclose the name of a generic placeholder in angle brackets, like this: `struct Queue<T> {`. The `T` doesn't mean anything special—it could be `R` or `Element`—but `T` is commonly used.

	Here's a simple example of a generic function, where the `T` is a placeholder type:

	```swift
	func swapValues<T>(_ a: inout T, _ b: inout T) {
		let temp = a
		a = b
		b = temp
	}

	var a = 10
	var b = 20
	swapValues(&a, &b)  // a = 20, b = 10
	```

	We can also add constraints so generics only accept certain types. In the following example, `findLargestElement` only works with types that conform to `Comparable`.

	```swift
	func findLargestElement<T: Comparable>(in array: [T]) -> T? {
		guard !array.isEmpty else {
			return nil
		}
		return array.max()
	}
	```
	
	To use the function, we can pass in an array of any type that conforms to the `Comparable` protocol, such as integers, doubles, or strings:

	```swift
	let numbers = [1, 4, 2, 5, 3]
	let largestNumber = findLargestElement(in: numbers)
	print(largestNumber) // Output: Optional(5)

	let names = ["John", "Alice", "Bob", "Eve"]
	let largestName = findLargestElement(in: names)
	print(largestName) // Output: Optional("John")
	```
	</details>

- 🟧 [What are multi-pattern `catch` clauses?](https://www.hackingwithswift.com/interview-questions/what-are-multi-pattern-catch-clauses)
	<details>
		<summary>Answer</summary>

	Multi-pattern `catch` clauses are a feature in Swift that allows us to catch and handle different types of errors with a single catch block using by using a comma-separated list of patterns. In previous versions of Swift, we would need to write multiple catch blocks to handle different types of errors, which could result in redundant code.

	Here's an example:

	```swift
	enum NetworkError: Error {
		case notConnected
		case timeout
	}
 
	do {
		// some code that can throw different types of errors
	} catch is NetworkError.notConnected, NetworkError.timeout {
		// handle network and database errors
	} catch {
		// handle other types of errors
	}
	```

	In this example, we use a multi-pattern `catch` clause to handle both `.notFound` and `.unreadable` errors in a single block.

	The `catch` statement can match error types, not just specific error values. This lets us to catch broad categories of errors, such as decoding or networking errors, rather than only exact enum cases.

	The example below illustrates how to use multiple type matches in a single `catch` clause using the `|` (pipe) operator.

	```swift
	do {
		throw URLError(.timedOut)
	} catch is DecodingError | URLError {
		print("Either a decoding issue or a network timeout")
	}
	```

  	Explanation:
	- `throw URLError(.timedOut)` simulates a function throwing a specific error—in this case, a `URLError`, which represents a network error.
	- The `catch is DecodingError | URLError` line is a multi-pattern catch clause using the `|` operator. It means: "If the error is either a `DecodingError` or a `URLError`, run this block."
	- The `is` keyword is used to match the type of the error.
	- If the error thrown matches any one of the types listed (in this case, `URLError`), the `print` statement runs.
	<br>
	
	Multi-pattern catch clauses can help reduce code duplication and make error handling more concise and readable. However, it's important to use them judiciously, as too many patterns in a single catch block can make it harder to understand and maintain our code.
	</details>

- 🟧 [What does the `@main` attribute do?](https://www.hackingwithswift.com/interview-questions/what-does-the-atmain-attribute-do)
	<details>
		<summary>Answer</summary>

	In Swift, the `@main` attribute is used to mark a specific class as the entry point for the application. This attribute was introduced in Swift 5.3 and replaces the traditional `main.swift` file that was used to define the entry point in earlier versions of Swift.

	When we mark a class with the `@main` attribute, the Swift compiler generates a `main` function that instantiates an instance of the marked class and invokes its `main` method. This allows us to define our application's entry point using a regular class, rather than a separate file.

	Here's an example of how to use the `@main` attribute:

	```swift
	@main
	struct MyApplication {
		static func main() {
			// application code here
		}
	}
	```
	
	In this example, we define a `MyApplication` struct and mark it with the `@main` attribute. We then define a `main` method inside the struct, which is automatically invoked when the application is launched.

	The `@main` attribute can be used to mark any type that conforms to the `App` protocol, which requires the implementation of a `main` method. This protocol provides a default implementation of the `main` method, so we don't have to define it ourselves.

	Using the `@main` attribute can simplify the structure of our application by allowing us to define the entry point in the same file as the rest of our code. It can also make our code more readable by making it clear where the application starts.
	</details>

- 🟧 [What does the `#available` syntax do?](https://www.hackingwithswift.com/interview-questions/what-does-the-available-syntax-do)
	<details>
		<summary>Answer</summary>

	The `#available` syntax in Swift is used to safely check the OS or platform version at runtime before running code that may only be supported in newer system versions. It helps us prevent crashes from calling APIs that aren't available on older versions of iOS, macOS, or other platforms.

	Here's an example:

	```swift
	if #available(iOS 14, macOS 11, *) {
		// use new API or feature only available in iOS 14 and macOS 11
	} else {
		// use older API or feature for backward compatibility
	}
	```

	In this example, we use the `#available` syntax to check whether the new API or feature is available on the current platform. If it is available (i.e., the current platform is iOS 14 or macOS 11), we can use it. If it is not available, we can fall back to an older API or feature that is still supported on the current platform.

	The `#available` syntax takes a comma-separated list of operating system or platform names and version numbers, followed by an asterisk (`*`) that represents any other platforms that are not explicitly listed. We can also use the `@available` attribute to mark a function or variable as being available on certain platforms.
	</details>

- 🟧 [What is a variadic function?](https://www.hackingwithswift.com/interview-questions/what-is-a-variadic-function)
	<details>
		<summary>Answer</summary>

	A variadic function in Swift is a function that can accept zero or more values of a specific type as a single parameter. This is useful when we want to allow callers to pass in a flexible number of arguments, rather than a fixed count. The number of arguments passed to the function can vary at runtime, and the function can process them as a single collection of values.
 
	To define a variadic function in Swift, we need to use the ellipsis (`...`) after the argument's type. Here's an example:

	```swift
	func sum(numbers: Int...) -> Int {
		var total = 0
		for number in numbers {
			total += number
		}
		return total
	}
	```
	
	In this example, the `sum` function takes an arbitrary number of integer arguments using the `Int...` syntax. The function can then iterate over the collection of values passed in and sum them.

	To call a variadic function, we can pass any number of values of the specified type, separated by commas. For example:

	```swift
	let result = sum(numbers: 1, 2, 3, 4)
	print(result)  // Output: 10
	```

	It's important to note that we can only have **one variadic parameter per function**, and it must be the **last** in the parameter list.

	Variadic functions can be useful for working with collections of values, such as arrays or lists, or for providing flexible interfaces that can accept a variable number of arguments. They are commonly used in Swift standard library functions, such as `print` and `min`, and can be a powerful tool for simplifying our code and making it more flexible.
	</details>

- 🟧 [What is the difference between `weak` and `unowned`?](https://www.hackingwithswift.com/interview-questions/what-is-the-difference-between-weak-and-unowned)
	<details>
		<summary>Answer</summary>

	The difference between `weak` and `unowned` in Swift comes down to how they handle memory ownership and optional vs. non-optional references. Both are used to avoid retain cycles in closures or between objects, but they behave differently when the referenced object is deallocated.

	Here's a table representing the core differences:

	<table>
		<tr>
			<th>FEATURE</th>
			<th><code>weak</code></th>
			<th><code>unowned</code></th>
		</tr>
		<tr>
			<td><strong>Optional</strong></td>
			<td>Yes (<code>var x: Type?</code>)</td>
			<td>No (<code>var x: Type</code>)</td>
		</tr>
		<tr>
			<td><strong>Becomes nil</strong></td>
			<td>Yes</td>
			<td>No</td>
		</tr>
		<tr>
			<td><strong>Safe access</strong></td>
			<td>Safe (optional binding)</td>
			<td>Crashes if accessed after dealloc</td>
		</tr>
		<tr>
			<td><strong>Use when</strong></td>
			<td>Referenced object may become <code>nil</code></td>
			<td>Object must outlive the reference</td>
		</tr>
	</table>
	
	`weak` is used when one object refers to another, but shouldn't keep it alive. For example, in a delegate pattern, a child object might have a reference to its parent. Making this reference `weak` ensures the child doesn't keep the parent alive indefinitely. `weak` references must always be declared as optional, since the object they point to can be deallocated at any time—and when that happens, the reference is automatically set to `nil`. This prevents dangling pointers and makes the code safe.

	```swift
	class Owner {
		var pet: Pet?

		deinit {
			print("Owner deinitialized")
		}
	}

	class Pet {
		weak var owner: Owner?  // weak reference

		deinit {
			print("Pet deinitialized")
		}
	}

	var john: Owner? = Owner()
	var fluffy: Pet? = Pet()

	john?.pet = fluffy
	fluffy?.owner = john  // no strong reference cycle

	john = nil
	fluffy = nil

	// Output:
	// "Owner deinitialized"
	// "Pet deinitialized"
	```

	On the other hand, `unowned` is similar to `weak`, but it's used when the referring object is guaranteed to outlive the object it references. Unlike `weak`, an `unowned` reference is non-optional. This is a performance optimization, but it comes with a trade-off: if the referenced object is deallocated and the `unowned` reference is accessed, the app will crash. Therefore, we should only use `unowned` when we're certain of the ownership relationship, such as in closures where the lifecycle is tightly controlled. It's safer to just use `weak`, as `unowned` is rarely used because it can cause the app to crash.

	```swift
	class Customer {
		var creditCard: CreditCard?

		deinit {
			print("Customer deinitialized")
		}
	}

	class CreditCard {
		unowned var owner: Customer  // unowned reference

		init(owner: Customer) {
			self.owner = owner
		}

		deinit {
			print("CreditCard deinitialized")
		}
	}

	var john: Customer? = Customer()
	john?.creditCard = CreditCard(owner: john!)  // No cycle

	john = nil

	// ✅ Output:
	// "Customer deinitialized"
	// "CreditCard deinitialized"
	```

	When in doubt, it's better to use `weak` to avoid any crashes.
	</details>

- 🟧 [What is the difference between an escaping closure and a non-escaping closure?](https://www.hackingwithswift.com/interview-questions/what-is-the-difference-between-an-escaping-closure-and-a-non-escaping-closure)
	<details>
		<summary>Answer</summary>

	The difference between an escaping and non-escaping closure in Swift comes down to when and where the closure is executed in relation to the function it's passed into.

	Here's a table that breaks down the core differences:

	<table>
		<tr>
			<th>CLOSURE TYPE</th>
			<th>EXECUTES...</th>
			<th>BEHAVIOR</th>
		</tr>
  		<tr>
			<td><strong>Non-escaping</strong></td>
			<td>During the function call</td>
			<td>Executed immediately and finishes before the function ends</td>
		</tr>
  		<tr>
			<td><strong>Escaping</strong></td>
			<td>After the function call completes</td>
			<td>Stored and called later (e.g., in async code, completion handlers)</td>
		</tr>
	</table>

	A non-escaping closure is a closure that is guaranteed to be executed synchronously within the same function scope in which it is passed. This means that the closure is executed while the function is still running, and it is not stored or used outside the function. Non-escaping closures are the default in Swift, which means that we don't need to use any special annotations to mark them.

	An escaping closure, on the other hand, is a closure that is allowed to escape the function scope and be called after the function has returned. This means that the closure is executed at a later time, possibly on a different thread, and it may be stored or used outside the function. To indicate that a closure is escaping, we need to mark it with the `@escaping` attribute.

	Here's an example that shows the difference between an escaping and a non-escaping closure:

	```swift
	func performOperationNonEscaping(withNumber number: Int, operation: (Int) -> Int) -> Int {
		// The closure is executed synchronously within the function scope
		let result = operation(number)
		return result
	}

	func performOperationEscaping(withNumber number: Int, operation: @escaping (Int) -> Int) {
		// The closure is stored and executed asynchronously outside of the function scope
		DispatchQueue.main.async {
			let result = operation(number)
			print(result)
		}
	}

	// Example usage of the non-escaping closure
	let square = performOperationNonEscaping(withNumber: 5) { (num) -> Int in
		return num * num
	}
	print(square) // Output: 25

	// Example usage of the escaping closure
	performOperationEscaping(withNumber: 5) { (num) -> Int in
		return num * num
	}
	// Prints `25`, but asynchronously, so it may appear after other print statements depending
	// on timing.
	```

	In this example, `performOperationNonEscaping` takes a non-escaping closure that squares a number synchronously within the same function. On the other hand, `performOperationEscaping` takes an escaping closure that squares a number asynchronously on a different thread, after the function has returned. The `DispatchQueue.main.async` call ensures that the closure is executed on the main thread, which is required for UI updates. Note that `performOperationNonEscaping` doesn't result anything, so we can't assign it to a variable like did with `performOperationNonEscaping`.

	In general, non-escaping closures are simpler and safer to use than escaping closures because they don't require extra memory management considerations. However, escaping closures are necessary when we need to perform asynchronous operations, such as networking or animation, and we need to handle the results of those operations at a later time.
	</details>

- 🟧 [What is the difference between an extension and a protocol extension?](https://www.hackingwithswift.com/interview-questions/what-is-the-difference-between-an-extension-and-a-protocol-extension)
	<details>
		<summary>Answer</summary>

	A regular extension adds new functionality—like methods, computed properties, initializers, or nested types—to an existing type, such as a class, struct, enum, or even another protocol.

	Here's an example:

	```swift
	extension String {
		func reversedWords() -> String {
			return self.split(separator: " ").reversed().joined(separator: " ")
		}
	}
	
	let text = "Hello world"
	print(text.reversedWords())  // Output: "world Hello"
	```

	We added a method to the `String` class that only works for `String` and doesn't affect other types.

	A protocol extension, on the other hand, is a way to provide default implementations for a protocol's requirements. Protocol extensions can add new methods, properties, subscripts, and associated types to a protocol, and provide default implementations for them. Protocol extensions can also provide default implementations for protocol methods and properties, which can be overridden by the adopting types if needed.

	The main difference between an extension and a protocol extension is their purpose and scope. It's like saying, "All types that conform to this protocol will automatically get this behavior unless they override it."

	Here's an example:

	```swift
	protocol Greetable {
		func greet()
	}
	
	extension Greetable {
		func greet() {
			print("Hello from Greetable!")
		}
	}
	
	struct Person: Greetable {}
	Person().greet()  // Output: Hello from Greetable!
	```

	In this example, we added a default `greet()` method to any type that conforms to `Greetable`. However, we can still override the default implementation in a specific type.

	In summary, use regular extensions to add specific functionality to a concrete type. Conversely, use protocol extensions to define shared default behavior for multiple types that conform to a protocol.
	</details>
	
- 🟧 [When would you use the `defer` keyword in Swift?](https://www.hackingwithswift.com/interview-questions/when-would-you-use-the-defer-keyword-in-swift)
	<details>
		<summary>Answer</summary>

	In Swift, the `defer` keyword is used to guarantee that certain code is executed at the very end of the current scope, regardless of how that scope exits—whether normally or due to an error, `return`, or early exit.

	In other words, `defer` is perfect for cleanup tasks, such as closing files, releasing resources, stopping animations, or resetting state.

	Here are some common scenarios where we might use `defer`:

	1. **Resource cleanup**: We can use `defer` to ensure that resources such as files, network connections, and database connections are properly closed or released, regardless of how a function or method exits. For example:

		```swift
		func readFile(atPath path: String) throws -> String {
			let file = try FileHandle(forReadingFrom: URL(fileURLWithPath: path))
			defer {
				file.closeFile()
			}
			let data = file.readDataToEndOfFile()
			return String(data: data, encoding: .utf8)!
		}
		```
	
		In this example, we use the `defer` statement to ensure that the file handle is closed, regardless of whether the function throws an error or not.

	2. **Releasing locks**: When working with concurrent or multithreaded code, it's common to use locks (like `NSLock`, `DispatchSemaphore`, or `pthread_mutex`) to protect shared resources. If we acquire a lock but forget to release it—due to an early return, an error, or a complex control flow—we can easily introduce deadlocks, which are notoriously hard to debug.
	
		```swift
		func doSomething() throws {
			let lock = NSLock()
			lock.lock()
			defer {
				lock.unlock()
			}
			// Do something that requires the lock
		}
		```
		
		This pattern ensures that the lock is always released, no matter how the function exits. Without `defer`, we'd need to manually release the lock in multiple places, which is error-prone.
	
	3. **Resetting temporary state**: Sometimes we need to temporarily change global or shared state—like modifying a flag, changing logging behavior, or toggling a UI element. It's easy to forget to reset the state if the code path has multiple exits (e.g., error handling or early returns).

		```swift
		func animateView() {
			startLoadingAnimation()
			defer {
				stopLoadingAnimation()
			}
		
			// Perform some work
		}
		```

		With `defer`, we make the cleanup predictable and robust, even when the logic gets complicated.

	We can use multiple `defer` blocks within the same scope (typically inside a function or method). Each `defer` block is executed when the scope exits, but there's one key rule: Multiple `defer` blocks execute in reverse order—last-in, first-out (LIFO).

	This behavior mirrors how a stack works: the last `defer` we add is the first one that runs. This gives us predictable and orderly cleanup when multiple resources or operations need to be reversed or undone in a specific order.

	```swift
	func multipleDefers() {
		defer { print("First") }
		defer { print("Second") }
		defer { print("Third") }
	}
	multipleDefers()
	// Output: Third, Second, First
	```

	In summary, we can use `defer` to ensure that certain actions are performed at the end of a scope, regardless of how the scope is exited. It is useful for resource cleanup, resource acquisition, and clean-up tasks.
	</details>
	
- 🟥 [How would you explain key paths to a new Swift developer?](https://www.hackingwithswift.com/interview-questions/how-would-you-explain-key-paths-to-a-new-swift-developer)
	<details>
		<summary>Answer</summary>

	In Swift, key paths are a way to refer to a property of a type—like a pointer to that property—, not the value itself. They provide a type-safe way to do this, eliminating the need for boilerplate code.

	A key path is represented as a path of property names separated by dots, e.g. `\Person.name`. Key paths are strongly typed, meaning that the type of the key path is determined by the type of the property it refers to.

	One way to use key paths is to access or modify properties of an object. For example:

	```swift
	struct Person {
		var name: String
		var age: Int
	}
	
	let nameKeyPath = \Person.name
	print(nameKeyPath)  // Swift.KeyPath<Person, String>
	```

	`\Person.name` is a key path to the name property on `Person`. It doesn't access the value yet, it just describes where to find it.

	Another way to use key paths is with higher-order functions, such as `map`, `filter`, `sorted`, and `reduce`. For example:
	
	```swift
	let people = [Person(name: "Bob", age: 40), Person(name: "Alice", age: 30)]

	let sorted = people.sorted { $0[keyPath: \Person.age] < $1[keyPath: \Person.age] }
	```
	
	In this example, we sort using the `age` key path; no need to access the property directly.

	Key paths are useful when:
	- We want to write generic or reusable code that works with different properties.
	- We're using APIs like `sort`, `map`, or `filter` and want to reference a property concisely.
	- We're working with bindings or data-driven UI (like SwiftUI).
	</details>

- 🟥 [What are conditional conformances?](https://www.hackingwithswift.com/interview-questions/what-are-conditional-conformances)
	<details>
		<summary>Answer</summary>
	
	Conditional conformances in Swift let a generic type conform to a protocol only when certain conditions are met—typically when its generic parameters themselves conform to a required protocol.

 	In natural language, instead of saying: "This type always conforms to protocol X," we would say, "This type only conforms to protocol X if its generic type meets condition Y."

	Here's an example:

	```swift
	struct Box<T> {
		let value: T
	}
		
	// Make Box conform to Equatable only if T does
	extension Box: Equatable where T: Equatable {
		static func == (lhs: Box<T>, rhs: Box<T>) -> Bool {
			return lhs.value == rhs.value
		}
	}
	
	let a = Box(value: 5)
	let b = Box(value: 5)
	print(a == b)  // ✅ Works because Int is Equatable
	
	let x = Box(value: NSObject())
	// print(x == x) ❌ Error: NSObject isn't Equatable, so Box<NSObject> isn't either
	```

	Conditional conformances avoid forcing all generic types to implement behaviors they may not support. They are essential when working with collections, wrappers, or containers that only make sense under certain type constraints.
	</details>

- 🟥 [What are opaque return types?](https://www.hackingwithswift.com/interview-questions/what-are-opaque-return-types)
	<details>
		<summary>Answer</summary>
	
	Opaque return types, introduced in Swift 5.1, allow us to declare a function's return type as a placeholder rather than a concrete type. The placeholder is an "opaque" type that hides the underlying implementation details of the return type while preserving type safety.

	An opaque return type is defined using the `some` keyword followed by a type, like this:

	```swift
	func makeShape() -> some Shape {
		return Circle(radius: 10)
	}
	```

	Here, the `makeShape` function returns a type that conforms to `Shape`, but the concrete type is not revealed to the caller. This means that the implementation of `makeShape` can be changed in the future without affecting the caller's code, as long as the new implementation still returns a value that conforms to the `Shape` protocol.

	Opaque return types are particularly useful when we want to return a type that is only known to the implementation of the function, but not to the caller. For example, we might have a function that creates and returns a view, but the type of the view depends on the implementation details of the function:

	```swift
	func makeView() -> some View {
		if someCondition {
			return Button("OK") { }
		} else {
			return Text("Hello, world!")
		}
	}
	```
	
	Here, the concrete type of the view returned by `makeView` depends on the value of `someCondition`, which is not known to the caller. By using an opaque return type, we can hide this implementation detail and present a simpler and more flexible interface to the caller.

	Now that we know what opaque return types are, we need to undestand between them and protocol return types. Let's break down teh difference between `-> Animal` and `-> some Animal`.

	```swift
	func makeAnimal() -> Animal {
		return Dog()  // could also return Cat(), Bird(), etc.
	}
 	```

	This says: "I'll return any kind of `Animal`, and I don't care which". Internally, Swift boxes the value and treats it dynamically, like an abstract interface.

	In fact, we can also do this:

	```swift
	func makeAnimal(random: Bool) -> Animal {
		return random ? Dog() : Cat()  // ✅ OK
	}
	```

	However, there are downsides to this approach. We lose static type information, as the compiler no longer knows what concrete type we're working with. Also, the method dispatch is slower because it's dynamic.

	On the other hand, here's what we'd do for `-> some Animal`:

  	```swift
	func makeAnimal() -> some Animal {
		return Dog()
	}
	```

	This says: "I'm returning a specific type that conforms to `Animal`, but I'm hiding the exact type." The caller doesn't know it's a `Dog`, but the compiler does and treats it statically. We must return the same concrete type every time—we can’t switch:

	```swift
	func makeAnimal(random: Bool) -> some Animal {
		return random ? Dog() : Cat()  // ❌ Error — must return one consistent type
	}
	```

	One advantage of this approach is that it retains static type safety and performance (there is no boxing or dynamic dispatching). This approach also works very well with SwiftUI views, generics, and library design.

	This summary table indicates when to use each:

	<table>
		<tr>
			<th>USE CASE</th>
			<th>USE <code>-> Animal</code></th>
			<th>USE <code>-> some Animal</code></th>
		</tr>
		<tr>
			<td><strong>Return different types</strong></td>
			<td>✅</td>
			<td>❌ Must be one type</td>
		</tr>
		<tr>
			<td><strong>Want maximum abstraction</strong></td>
			<td>✅</td>
			<td>✅</td>
		</tr>
		<tr>
			<td><strong>Want performance/type safety</strong></td>
			<td>❌ Slower dispatch</td>
			<td>✅ Static, faster</td>
		</tr>
		<tr>
			<td><strong>Building SwiftUI views</strong></td>
			<td>❌ Not allowed</td>
			<td>✅ Required</td>
		</tr>
	</table>
	</details>

- 🟥 [What are result builders and when are they used in Swift?](https://www.hackingwithswift.com/interview-questions/what-are-result-builders-and-when-are-they-used-in-swift)
	<details>
		<summary>Answer</summary>

	A result builder, introduced in Swift 5.4, is a custom attribute (marked with @resultBuilder) that transforms a series of statements (like function calls or conditionals) into a single return value, by combining or composing them. They're most famously used in SwiftUI.

	Result builders are essentially a way to transform a series of expressions and statements into a single value of a specific type. They are implemented using a combination of function builders and property wrappers, which provide a way to collect and transform a sequence of values into a final result.
	
	In SwiftUI, result builders are used to declaratively build user interfaces, as shown in the following example:

	```swift
	struct ContentView: View {
		var body: some View {
		VStack {
			Text("Hello")
			if Bool.random() {
				Text("Random message")
			}
				Text("World")
			}
		}
	}
	```
	
	`VStack { ... }` uses a result builder. It combines multiple `Text` views (and even an `if`) into one composite view. This works because `VStack` initializer is annotated with a result builder (`@resultBuilder`).

	Here's an example of what a result builder does under the hood:

	```swift
	Text("Hello")
	Text("World")

	// Transformed into
	TupleView<(Text, Text)>
	```

	Here's a custom result builder example:

	```swift
 	// Step 1: Define the builder
	@resultBuilder
	struct StringListBuilder {
		static func buildBlock(_ components: String...) -> [String] {
			return components
		}
	}

	// Step 2: Use it
	func makeList(@StringListBuilder content: () -> [String]) -> [String] {
		content()
	}
	
	let items = makeList {
		"Apple"
		"Banana"
		"Cherry"
	}
	print(items)  // ["Apple", "Banana", "Cherry"]
	```
	</details>

- 🟥 [What does the `targetEnvironment()` compiler condition do?](https://www.hackingwithswift.com/interview-questions/what-does-the-targetenvironment-compiler-condition-do)
	<details>
		<summary>Answer</summary>

	The `targetEnvironment()` compiler condition is a part of Swift's build configuration system that allows developers to check the target environment of their code at compile-time. This is useful when writing code that is intended to run on multiple platforms or operating systems, as different platforms may require different code paths or behaviors.

	The `targetEnvironment()` condition takes a single argument, which can be one of several predefined values:

	- `simulator`: Evaluates to true when the code is being compiled for a simulator platform, such as the iOS Simulator or the macOS Simulator.
	- `macCatalyst`: Evaluates to true when the code is being compiled for a Mac Catalyst app, which is an iOS app that has been adapted to run on macOS.
	- `os`: Evaluates to true when the code is being compiled for a specific operating system, such as `os(macOS)` or `os(iOS)`.
	- `arch`: Evaluates to true when the code is being compiled for a specific processor architecture, such as `arch(x86_64)` or `arch(arm64)`.
	<br />
	
	Here's an example of how to use the `targetEnvironment()` condition in Swift:

	```swift
	#if targetEnvironment(macCatalyst)
	// Code to run when compiling for Mac Catalyst
	#elseif os(iOS)
	// Code to run when compiling for iOS
	#elseif os(macOS)
	// Code to run when compiling for macOS
	#else
	// Code to run for other platforms
	#endif
	```

	A common use case is to distinguish between running on a real iOS device or a simulator:

  	```swift
	#if targetEnvironment(simulator)
	print("Running in the Simulator")
	#else
	print("Running on a real device")
	#endif
	```

	This is often used to mock hardware, skip certain features (like Face ID), or avoid crashing when trying to access unsupported device APIs.
	</details>

- 🟥 [What is the difference between `self` and `Self`?](https://www.hackingwithswift.com/interview-questions/what-is-the-difference-between-self-and-self)
	<details>
		<summary>Answer</summary>

	>- `self` → instance
	>- `Self` → type

	In Swift, `self` (with a lowercase "s") refers to the current instance of a class, struct, or enum, while `Self` (with an uppercase "S") refers to the type of the current instance.

	The `self` keyword is commonly used within an instance method or initializer to refer to the instance itself, for example:

	```swift
	class Person {
		var name: String
	
		init(name: String) {
			self.name = name // "self" refers to the current instance of Person
		}
	}
	```
	
	On the other hand, `Self` is typically used when defining a method or property that returns an instance of the current type. This is known as a "static dispatch" or "static return type" because the type is determined at compile time rather than runtime.

	Here's an example:

	```swift
	class Animal {
		static func create() -> Self {
			return self.init()
		}
	}

	class Dog: Animal {
		var name: String
	
		init(name: String) {
			self.name = name
		}
	}

	let myDog = Dog.create() // "create" returns a Dog instance
	```
	
	In this example, the `create` method on the `Animal` class returns an instance of the current type (`Self`) using the `init` method. When the `create` method is called on the `Dog` class, it returns an instance of `Dog`.
	</details>

- 🟥 [When would you use `@autoclosure`?](https://www.hackingwithswift.com/interview-questions/when-would-you-use-atautoclosure)
	<details>
		<summary>Answer</summary>
	
	In Swift, the `@autoclosure` attribute is used to automatically wrap an expression in a closure. This means that the expression is not evaluated until it is called, allowing for deferred execution and lazy evaluation. This can be useful in certain situations where the expression is expensive to evaluate, or when we want to avoid evaluating the expression unless it is necessary.

	`@autoclosure` automatically wraps an expression in a closure—so instead of writing:

	```swift
	someFunction({ expensiveComputation() })
	```

	We can write:
 
	```swift
	someFunction(expensiveComputation())
	```

	And Swift will automatically wrap it as `() -> ResultType`.

  	As an example of use, Swift's `assert()` function uses `@autoclosure`:

  	```swift
	assert(2 + 2 == 4, "Math broke")
	```

	Under the hood, the condition is an `@autoclosure`:

  	```swift
	func assert(_ condition: @autoclosure () -> Bool, _ message: @autoclosure () -> String)
	```

	The condition and message are not evaluated unless necessary (e.g., in debug builds). Also, we don't have to wrap them in `{ }` closures.

	Here's a custom example:

	```swift
	func logIfNeeded(_ message: @autoclosure () -> String) {
		#if DEBUG
		print(message())
		#endif
	}
	
	logIfNeeded("Something went wrong")  // You pass a string, not a closure
	```

	The string won’t be built unless `DEBUG` is true.

	Overall, `@autoclosure` is useful when:
	- The argument is expensive to compute.
 	- We want to delay or run it conditionally.
  	- We want to improve API ergonomics (no `{ }` needed from the caller).
  	<br>

	Note that, since `@autoclosure` delays evaluation, anything with side effects (e.g., modifying a variable, logging, incrementing) might not run at all or run later than expected.
	</details>

<p align="right">(<a href="#top">back to top</a>)</p>

## SwiftUI

- 🟩 [How would you explain SwiftUI's environment to a new developer?](https://www.hackingwithswift.com/interview-questions/how-would-you-explain-swiftuis-environment-to-a-new-developer)
	<details>
		<summary>Answer</summary>
	
	In SwiftUI, the environment is a way to pass shared data or settings automatically through the view hierarchy—from parent to child—without explicitly injecting it into every view.

	Think of it as a set of global values that any SwiftUI view can read or respond to, like:
	- System settings (e.g., dark mode, locale, accessibility).
	- App-wide values (e.g., user preferences, layout direction).
	- Custom values we inject ourselves (e.g., theme color, auth state).
	<br>

 	To establish a simple analogy, imagine we're building a house (the app) and that the environment is the air—all rooms (views) can breathe it. We don't have to run wires (pass data manually) to every single room.

	One of the main benefits of using the environment is that it allows us to create a consistent user interface throughout our app. For example, we might use the `.font` environment key to set a default font for all our app's text views. If the user changes the font size in the system settings, all the text in our app will automatically update to reflect the new font size.

	SwiftUI includes many useful system-provided environment values:

	```swift
	@Environment(\.colorScheme) var colorScheme
	@Environment(\.locale) var locale
	@Environment(\.horizontalSizeClass) var sizeClass
	```

	We can also define custom environment values to share app-level state or configuration:

	```swift
	// Step 1: Define a shared model
	struct UserSettings: ObservableObject {
		@Published var isLoggedIn: Bool = false
	}

	// Step 2: Inject it into the app's view hierarchy
	@main
	struct MyApp: App {
		@StateObject var settings = UserSettings()
		
		var body: some Scene {
			WindowGroup {
				ContentView()
					.environmentObject(settings)  // This injects the model into the environment
			}
		}
	}

	// Step 3: Access it in any child view
	struct ContentView: View {
		@EnvironmentObject var settings: UserSettings
		
		var body: some View {
			Text(settings.isLoggedIn ? "Welcome back!" : "Please log in.")
		}
	}
 	```

	`.environmentObject(settings)` adds the `UserSettings` object to the environment, allowing any subsequent view to access it. Additionally, we don't need to manually pass `settings` as a parameter in the `ContentView`, as SwiftUI automatically looks up the environment to find `UserSettings`.

	The `@Environment` property wrapper is used to access system-provided settings, such as dark mode, locale, and font. `@EnvironmentObject`, on the other hand, is used to access custom environment values, such as the user's session or settings.
	</details>

- 🟩 [What does the `@Published` property wrapper do?](https://www.hackingwithswift.com/interview-questions/what-does-the-atpublished-property-wrapper-do)
	<details>
		<summary>Answer</summary>
	
	The `@Published` property wrapper in Swift is used inside an `ObservableObject` to automatically announce changes to a property so that SwiftUI views (or other observers) can react and update when the value changes.

	Marking a property with `@Published` automatically creates a publisher for that property. This publisher will emit a new value whenever the value of the property changes, which will also trigger the `objectWillChange` publisher of the `ObservableObject` that SwiftUI observes to trigger UI updates. This eliminates the need to manually send updates or notifications when the value of the property changes, as Combine handles it automatically.

	Here's an example:

	```swift
	import SwiftUI
	import Combine
	
	class Counter: ObservableObject {
		@Published var count: Int = 0
	}
	
	struct ContentView: View {
		@StateObject private var counter = Counter()
	
		var body: some View {
			VStack {
				Text("Count: \(counter.count)")
				Button("Increment") {
					counter.count += 1
				}
			}
		}
	}
	```
	
	- `@Published var count: Int`: Marks the `count` property as a publisher. Any changes to `count` will notify subscribers.
 	- `@StateObject`: Used in SwiftUI to create and observe the `Counter` instance. SwiftUI listens to changes in the `objectWillChange` publisher and updates the UI automatically.
	<br>
	
	Common pitfalls:
	- **Not for structs or enums**: `@Published` works only in classes because it relies on reference semantics and the `ObservableObject` protocol.
 	- **Default behavior**: If we don't observe an `ObservableObject` instance properly in SwiftUI (e.g., by using `@StateObject` or `@ObservedObject`), the UI won't react to changes in `@Published` properties.
  	- **Non-thread-safe**: Modifying `@Published` properties from non-main threads without ensuring thread safety can lead to unexpected behavior in the UI.
	</details>

- 🟩 [What does the `@State` property wrapper do?](https://www.hackingwithswift.com/interview-questions/what-does-the-atstate-property-wrapper-do)
	<details>
		<summary>Answer</summary>

	The `@State` property wrapper in SwiftUI is used to declare a piece of state that is local to a view. It allows the view to own and manage its own mutable data—and automatically triggers a UI update whenever that data changes.

	In simple terms, `@State` is for temporary view-specific data—things like:
	- Whether a toggle is on or off.
	- A text field's input.
	- A counter's value.
	<br>

	SwiftUI watches that state, and when it changes, it re-renders the body of the view.

	Here's an example of how to use `@State` in a simple SwiftUI `View`:
	
	```swift
	import SwiftUI

	struct CounterView: View {
		@State private var count = 0  // @State makes `count` mutable inside the view

		var body: some View {
			VStack {
				Text("Count: \(count)")  // This view updates automatically
				Button("Increment") {
					count += 1  // Triggers view update
				}
			}
		}
	}
	```

	Here are some important rules to consider about `@State`:
	- `@State` variables are usually private because they are internal to the view and they shouldn't be read or written from outside.
	- It ensures that the state variable is only accessed from the main thread, which helps avoid race conditions and other concurrency issues.
	- `@State` can only be used in structs that conform to `View`.
	- We should not pass it directly to other views—instead, pass a binding via `$value`.
	- If we need to share state between multiple views or across our app, we should consider using `@ObservedObject` or `@EnvironmentObject` instead.
	</details>

- 🟩 [What's the difference between a view's initializer and `onAppear()`?](https://www.hackingwithswift.com/interview-questions/whats-the-difference-between-a-views-initializer-and-onappear)
	<details>
		<summary>Answer</summary>
	
	The initializer of a SwiftUI `View` is used to set up the initial state of the view, and is called only once during the lifetime of the view. On the other hand, the `onAppear()` modifier is called each time the view appears on the screen, and can be used to perform tasks such as fetching data, starting animations, or updating the view's state.

	Here's a simple example to illustrate the difference:

	```swift
	struct MyView: View {
		let message: String
	
		init() {
			message = "Hello, world!"
			print("Initializing view")
		}
	
		var body: some View {
			VStack {
				Text(message)
			}
			.onAppear {
				print("View appeared")
				fetchUserData()
			}
		}
	}
	```
	
	In this example, the `init()` method is called once to initialize the `message` property to "Hello, world!", and the `onAppear()` modifier is called each time the view appears on the screen to print "View appeared" to the console.

	**IMPORTANT**: Don't rely on the initializer for things like API calls or one-time logic, because SwiftUI may recreate the view multiple times. Use `onAppear` or `@State` to manage that instead.
	</details>

- 🟩 [When would you use `@StateObject` versus `@ObservedObject`?](https://www.hackingwithswift.com/interview-questions/when-would-you-use-atstateobject-versus-atobservedobject)
	<details>
		<summary>Answer</summary>
	
	In SwiftUI, both `@StateObject` and `@ObservedObject` are used to manage external state in a view, but the key distinction lies in who own and created the object.

	Here's a table pinpointing the core difference:

	<table>
		<tr>
			<th>PROPERTY WRAPPER</th>
			<th>OWNERSHIP</th>
			<th>RESPONSABILITY</th>
		</tr>
		<tr>
			<td><code>@StateObject</code></td>
			<td>Creates and owns the model</td>
			<td>Use when the view creates the object</td>
		</tr>
		<tr>
			<td><code>@ObservedObject</code></td>
			<td>References an external model</td>
			<td>Use when the object is created elsewhere</td>
		</tr>
	</table>
	
	Here's a simple example to illustrate the difference:

	```swift
	struct ParentView: View {
		@StateObject var viewModel = ProfileViewModel()
		
		var body: some View {
			ProfileView(viewModel: viewModel)  // Pass down as @ObservedObject
		}
	}
	
	struct ProfileView: View {
		@ObservedObject var viewModel: ProfileViewModel
		
		var body: some View {
			Text(viewModel.username)
		}
	}
	```
	
	In this example, the `ParentView` creates and owns the object (`@StateObject`). The `ProfileView` uses it (`@ObservedObject`), but doesn't own it.

	Beware that, if we use `@ObservedObject` to create a new object in a view, SwiftUI may recreate it every time the view reloads, causing bugs like loss of state, repeated API calls, and unwanted side effects. That's why `@StateObject` was introduced in Swift 5.3.
	</details>

- 🟧 [How can an observable object announce changes to SwiftUI?](https://www.hackingwithswift.com/interview-questions/how-can-an-observable-object-announce-changes-to-swiftui)
	<details>
		<summary>Answer</summary>
	
	An observable object can announce changes to SwiftUI by using the `@Published` property wrapper for the properties that need to trigger the updates. When a `@Published` property changes, the observable object will notify any SwiftUI views that are observing it.

	For example, let's say we have an observable object `UserData`:

	```swift
	import Combine

	class UserData: ObservableObject {
		@Published var name: String = ""
	}
	```
	
	And we have a view `UserView` that displays the username:

	```swift
	struct UserView: View {
		@ObservedObject var userData: UserData
	
		var body: some View {
			Text(userData.name)
		}
	}
	``` 
	
	When the `name` property of `UserData` changes, the `@Published` property wrapper will notify SwiftUI that the object has changed, and the `UserView` will be updated with the new value of `name`.

	Instead of `@Published`, we can use `objectWillChange.send()` for custom or manual update control. In fact, `@Published` uses this method under the hood.

	Here's the `UserData` class rewritten using `objectWillChange.send()` manually, instead of relying on `@Published`:

	```swift
	import Combine

	class UserData: ObservableObject {
		// The publisher used to notify SwiftUI of upcoming changes
		let objectWillChange = ObservableObjectPublisher()
		
		var name: String = "" {
			willSet {
				objectWillChange.send() // Notify SwiftUI before value changes
			}
		}
	}
	```
	</details>

- 🟧 [How would you create programmatic navigation in SwiftUI?](https://www.hackingwithswift.com/interview-questions/how-would-you-create-programmatic-navigation-in-swiftui)
	<details>
		<summary>Answer</summary>
	
	To create programmatic navigation in SwiftUI, where navigation is triggered by state changes and not just by tapping on links, we typically use one of these two approaches.

	1. **`NavigationLink` with a `Binding<Bool>` or `Binding<Optional>` destination**

		This is the most common method for simple programmatic navigation.

		Here's an example:

		```swift
		struct ContentView: View {
			@State private var isShowingDetail = false
		
			var body: some View {
				NavigationView {
					VStack {
						Button("Go to Detail") {
							isShowingDetail = true  // Trigger navigation
						}
			
						NavigationLink(
							destination: DetailView(),
							isActive: $isShowingDetail,
							label: { EmptyView() }  // Hidden link
						)
					}
				}
			}
		}
		
		struct DetailView: View {
			var body: some View {
				Text("Detail View")
			}
		}
		```

	2. **`NavigationStack` and `NavigationPath` APIs (iOS 16+)**

		For more complex flows or dynamic stacks, use `NavigationStack` and `NavigationPath`.

		Here's an example with push logic:

		```swift
		struct ContentView: View {
			@State private var path = NavigationPath()
			
			var body: some View {
				NavigationStack(path: $path) {
					VStack {
						Button("Go to Detail") {
							path.append("Detail")  // Push a new view
						}
					}
					.navigationDestination(for: String.self) { value in
						if value == "Detail" {
							DetailView()
						}
					}
				}
			}
		}
		```

		In this example, the entire stack is controlled via the path. In addition to pushing, we can also pop or clear views.
	</details>

- 🟧 [What is the purpose of the `ButtonStyle` protocol?](https://www.hackingwithswift.com/interview-questions/what-is-the-purpose-of-the-buttonstyle-protocol)
	<details>
		<summary>Answer</summary>
	
	The `ButtonStyle` protocol in SwiftUI defines how a button looks and reacts visually, allowing developers to customize its appearance and pressed-state behavior. It requires implementing a single method, `makeBody(configuration:)`, which returns a view describing the button's look.

	By conforming to `ButtonStyle`, we can create reusable, branded, or specialized styles and apply them to any `Button` instance. This is useful for maintaining consistent visual design and adding effects (like color changes or scaling) when the button is pressed.
	</details>

- 🟧 [When would you use `GeometryReader`?](https://www.hackingwithswift.com/interview-questions/when-would-you-use-geometryreader)
	<details>
		<summary>Answer</summary>
	
	`GeometryReader` is a view in SwiftUI that provides information about the size and position of its parent view, as well as its own size and position within its parent. It's useful in a variety of situations, such as:

	1. **Responsive layouts**:
		Get the size of the parent view to adjust the layout of child views to fit different screen sizes and orientations based on available space:

		```swift
		GeometryReader { geometry in
			Text("Hello")
				.frame(width: geometry.size.width * 0.8)
		}
		```

		This makes the text fill 80% of the parent's width.

	2. **Dynamic positioning**
		Get the size and position of the parent view to position child views within it using relative coordinates:

		```swift
		GeometryReader { geometry in
			Circle()
				.position(x: geometry.size.width / 2, y: geometry.size.height / 2)
		}
		```

		This centers the circle in its parent.

	3. **Parallax or scroll effects**: Get the position of a view on screen and react to it (e.g., scroll offset animations).

	4. **Debugging layouts**
		Print or inspect frame data during layout:

		```swift
		GeometryReader { geometry in
			Text("Width: \(geometry.size.width)")
		}
		```

 	Things to watch out for:
	- `GeometryReader` expands to fill all available space, so we should wrap it in a `ZStack` or `VStack`. Alternatively, we can use the `.frame()` method to constrain it.
	- It can be expensive if used excessively, so only use it when necessary.
	- Avoid nesting too many GeometryReaders, as this can make the layout more difficult to understand.
	</details>

- 🟥 [Why does SwiftUI use structs for views?](https://www.hackingwithswift.com/interview-questions/why-does-swiftui-use-structs-for-views)
	<details>
		<summary>Answer</summary>

	SwiftUI uses structs for views because they provide predictability, optimal performance, and simplicity, which aligns with the platform's declarative UI design philosophy.

	1. **Value semantics = Predictable behavior**: Structs are value types, which means that when a view is updated, a new copy is made. SwiftUI can then compare the old and new versions to determine what actually changed, which makes the rendering system more predictable and less error-prone than using reference type like classes.
	2. **Lightweight and fast**: Since structs don't require heap allocation or reference counting, they can be copied and discarded cheaply. This allows SwiftUI to optimize view diffing and updates.
	3. **Declarative = Immutable UI snapshots**: SwiftUI is declarative, meaning we describe what the UI should look like at any given time. Structs are perfect for this, as each view is a static snapshot of the UI state. If state changes, SwiftUI simply recomputes the view body from scratch using new structs.
	4. **Simple and clean code**: Structs make view code easier to read, safer to reason about and more aligned with Swift's focus on clarity and safety.
	</details>

<p align="right">(<a href="#top">back to top</a>)</p>

## UIKit

- 🟩 [How are XIBs different from storyboards?](https://www.hackingwithswift.com/interview-questions/how-are-xibs-different-from-storyboards)
	<details>
		<summary>Answer</summary>
	
	XIBs and storyboards are both ways of creating graphical user interfaces (GUIs) in iOS and macOS development, but they differ in some key ways.

	XIB files, also known as `.nib` files, are individual interface files that contain a single view or scene. They are used to build specific user interface elements that can be reused in different parts of an application. XIB files are typically used in conjunction with programmatic view controller code, which makes creating a custom UI possible without building all the UI elements in code.

	Storyboards, on the other hand, contain multiple scenes or views within a single file. They allow us to design and connect multiple screens of an app and make it easy to create and manage segues between screens. This makes designing the entire flow of an application's user interface possible in a single place, which makes visualization and management easier.

	Here are some key differences between XIBs and storyboards:

	1. **Structure**: XIBs contain a single view or scene, while storyboards contain multiple scenes or views.
	2. **Navigation**: Storyboards can be used to create the entire flow of an application's user interface, including navigation between different views, while XIBs are typically used to build specific views that are reused in multiple parts of an app.
	3. **Collaboration**: Since XIBs contain individual views, they can be more easily shared between developers, while storyboards are more complex and can be harder to manage in a team environment.
	4. **Flexibility**: XIBs provide more flexibility in terms of customizing individual views, while storyboards make it easier to manage the overall flow of an application's user interface.
	<br>

	In summary, XIBs are used to build individual views or UI elements that can be reused in different parts of an app, while storyboards are used to design the overall flow of an app's user interface.
	</details>

- 🟩 [How would you explain UIKit segues to a new iOS developer?](https://www.hackingwithswift.com/interview-questions/how-would-you-explain-uikit-segues-to-a-new-ios-developer)
	<details>
		<summary>Answer</summary>
	
	A segue is a visual and declarative way to transition from one view controller to another in a storyboard-based iOS app.

	There are four types of segues in UIKit:

	1. **Show (push)**: Pushes a new view controller onto the navigation stack. The new view controller slides in from the right, and the current view controller slides out to the left.
	2. **Modal (present)**: Presents a new view controller modally (fullscreen or sheet). The new view controller slides up from the bottom of the screen, covering the current view controller.
	3. **Popover**: Displays content in a popover (iPad-focused).
	4. **Custom**: Creates a custom transition between view controllers. It allows the developer to define a custom animation or transition effect.
	<br>

	Each segue has an identifier that is used to identify it in code. When a segue is triggered, the `prepare(for:sender:)` method is called on the current view controller, which allows the developer to pass data to the destination view controller before it is presented.

	Here's an example:

	```swift
	override func prepare(for segue: UIStoryboardSegue, sender: Any?) {
		if segue.identifier == "showDetail" {
			let destinationVC = segue.destination as! DetailViewController
			destinationVC.userName = "Alice"
		}
	}
	```
	</details>

- 🟩 [What are storyboard identifiers for?](https://www.hackingwithswift.com/interview-questions/what-are-storyboard-identifiers-for)
	<details>
		<summary>Answer</summary>
	
	Storyboard identifiers are used to identify a specific view controller within a storyboard. They are commonly used when navigating between view controllers programmatically, as they specify which view controller to present or push onto the navigation stack. When assigning a storyboard identifier to a view controller, we need to give it a unique string identifier, which can then be used in code to instantiate the view controller or perform a segue to it.

	Here's an example:

	```swift
	let storyboard = UIStoryboard(name: "Main", bundle: nil)
	let detailVC = storyboard.instantiateViewController(withIdentifier: "DetailViewController") as! DetailViewController
	navigationController?.pushViewController(detailVC, animated: true)
	```

	Without setting a Storyboard ID in Interface Builder, this code will crash.
	</details>

- 🟩 [What are the benefits of using child view controllers?](https://www.hackingwithswift.com/interview-questions/what-are-the-benefits-of-using-child-view-controllers)
	<details>
		<summary>Answer</summary>
	
	Using child view controllers can have several benefits, including:

	1. **Reusability**: After creating a child view controller, it can easily be reused in different parts of the app, thereby reducing the need for duplicate code.
	2. **Flexibility**: They offer greater flexibility in presentation and layout because views can be added or removed as needed. We can also animate transitions between them and repond to screen size or orientation changes with layout logic specific to each child.
	3. **Separation of concerns**: The parent manages layout and coordination, while children manage their own content and behavior.
	4. **Improved performance**: They improve app performance by enabling apps to load only the necessary views at a given time rather than loading all views simultaneously. This is particularly useful for apps with complex UIs that require a lot of resources to render.
	5. **Testing**: Each child can handle its own view model and interactions, so they can be unit tested or UI tested in isolation. This reduces dependencies between unrelated parts of the screen.
	6. **Lifecycle management**: They participate in the full `UIViewController` lifecycle. The events propagate from parent to child.
	<br>

	Here's an example:

	```swift
	let childVC = DetailViewController()
	addChild(childVC)
	view.addSubview(childVC.view)
	childVC.view.frame = container.bounds
	childVC.didMove(toParent: self)
	```

	</details>

- 🟩 [What are the pros and cons of using `viewWithTag()`?](https://www.hackingwithswift.com/interview-questions/what-are-the-pros-and-cons-of-using-viewwithtag)
	<details>
		<summary>Answer</summary>
	
	The `viewWithTag()` method is a way to retrieve a view from its superview by using a unique tag assigned to it. Here are some pros and cons of using it:

	✅ Pros: 
	- It is a quick and easy way to access a view from its superview without having to store a reference to it in a property.
	- It can be useful when dealing with dynamically generated views or when working with views that are not directly accessible in code (e.g. in a table view cell or collection view cell).
	<br>

	❌ Cons:
	- It can lead to code that is hard to read and maintain because the tag value is not easily discoverable in code.
	- It can be error-prone if multiple views have the same tag value or if the tag value is not unique.
	- It is less performant than directly accessing a view through a property because it requires the superview to search through its subviews to find the one with the specified tag.
	- It is not type-safe, as tags are just `Int`. There's no compile-time safety or autcomplete.
	<br>

	In short, it is generally recommended to avoid using `viewWithTag()` when possible and instead use `@IBOutlet` properties to store references to views that need to be accessed multiple times. However, in some cases where quick access to a view is needed and the tag value is guaranteed to be unique, using `viewWithTag()` can be a convenient solution.
	</details>

- 🟩 [What is the difference between `@IBOutlet` and `@IBAction`?](https://www.hackingwithswift.com/interview-questions/what-is-the-difference-between-atiboutlet-and-atibaction)
	<details>
		<summary>Answer</summary>
	
	`@IBOutlet` and `@IBAction` are annotations used with Interface Builder to connect user interface elements with code in Swift.

	`@IBOutlet` creates a reference to a UI element, such as a label, button, or text field. This allows the code to interact with the component by changing its properties, like text or color. It is always used with a `var` because UIKit needs to assign a value at runtime.

  	```swift
	@IBOutlet weak var nameLabel: UILabel!
	nameLabel.text = "Welcome!"
	```

	`@IBAction`, on the other hand, connects UI events (like button taps) to a method in the code. It must have a specific method signature the Interface Builder recognizes (usually returns `Void` and takes one parameter for the sender).

  	```swift
	@IBAction func submitButtonTapped(_ sender: UIButton) {
		print("Button was tapped!")
	}
	```

	This function gets called when the connected button is tapped.

	As a quick analogy, think of `@IBOutlet` as "reaching into the UI" to change it, and `@IBAction` as "responding to the UI" when something happens.
	</details>

- 🟩 [What is the difference between a `UIImage` and a `UIImageView`?](https://www.hackingwithswift.com/interview-questions/what-is-the-difference-between-a-uiimage-and-a-uiimageview)
	<details>
		<summary>Answer</summary>
	
	`UIImage` is the image itself and `UIImageView` other is a visual container that displays the image on the screen.

	A `UIImage` is a class that represents an image in memory. It does not display images itself, but rather, it is used as a data source for views that display images, such as a `UIImageView`.

	```swift
	let image = UIImage(named: "logo")
	```

	A `UIImageView`, on the other hand, is a subclass of `UIView` that displays a `UIImage` on screen. It is used in the view hierarchy to render images to users. We can apply layout, animations, tinting, and content modes to it.

	```swift
	let imageView = UIImageView(image: UIImage(named: "logo"))
	imageView.frame = CGRect(x: 0, y: 0, width: 100, height: 100)
	view.addSubview(imageView)
	```

	Now the image is visible inside the view.

	To understand the difference, consider the analogy of a photo and a photo frame. The photo is the `UIImage` and the frame is the `UIImageView`. We can't see the photo until it's placed in the frame and hung on the wall.
	</details>

- 🟩 [What is the difference between aspect fill and aspect fit when displaying an image?](https://www.hackingwithswift.com/interview-questions/what-is-the-difference-between-aspect-fill-and-aspect-fit-when-displaying-an-image)
	<details>
		<summary>Answer</summary>
	
	When displaying an image, aspect fill and aspect fit refer to two different ways of scaling the image to fit into the available space while maintaining its aspect ratio.

	Aspect fit (`.scaleAspectFit`) means that the image will be scaled so that it fits entirely within the available space, **without cropping**. This may leave empty space (padding) around the image, but ensures the whole image is visible.

	Aspect fill (`.scaleAspectFill`) means that the image will be scaled so that it completely fills the available space, even if that means cropping parts of the image to maintain its aspect ratio.

	In other words, aspect fit prioritizes displaying the entire image, while aspect fill prioritizes filling the entire space.

	Here's a table that sums up the differences:

	<table>
		<tr>
			<th>MODE</th>
			<th>BEHAVIOR</th>
			<th>PRESERVES ASPECT RATIO?</th>
			<th>MIGHT CROP?</th>
			<th>MIGHT ADD PADDING?</th>
		</tr>
		<tr>
			<td><code>.scaleAspectFit</code></td>
			<td>Fits image inside view</td>
			<td>✅ Yes</td>
			<td>❌ No</td>
			<td>✅ Yes</td>
		</tr>
		<tr>
			<td><code>.scaleAspectFill</code></td>
			<td>Fills view with image</td>
			<td>✅ Yes</td>
			<td>✅ Yes</td>
			<td>❌ No</td>
		</tr>
	</table>

	Here's an example of usage:

	```swift
	let imageView = UIImageView(image: UIImage(named: "photo"))
	imageView.contentMode = .scaleAspectFit  // or .scaleAspectFill
	```
	</details>

- 🟩 [What is the purpose of `UIActivityViewController`?](https://www.hackingwithswift.com/interview-questions/what-is-the-purpose-of-uiactivityviewcontroller)
	<details>
		<summary>Answer</summary>

	The purpose of the `UIActivityViewController` class is to provide a standard interface for sharing content or performing actions, such as sending text, images, URLs, or files via Messages, Mail, AirDrop, or social media, or saving them to the Files app.

	It's commonly referred to as the share sheet.

	Here's an example of usage:

	```swift
	let items = ["Check this out!", URL(string: "https://apple.com")!]
	let activityVC = UIActivityViewController(activityItems: items, applicationActivities: nil)
	present(activityVC, animated: true)
	```

	We can share texts, URLs, images, files, and custom data via `UIActivityItemSource`.

	We can even fine-tune what's shown to hide actions that don't make sense for the shared content:

	```swift
	activityVC.excludedActivityTypes = [.postToFacebook, .assignToContact]
	```
	</details>

- 🟩 [What is the purpose of `UIVisualEffectView`?](https://www.hackingwithswift.com/interview-questions/what-is-the-purpose-of-uivisualeffectview)
	<details>
		<summary>Answer</summary>
		
	The purpose of `UIVisualEffectView` in iOS is to apply visual effects to the views behind it. It provides a simple way to add blur and vibrancy effects to our app's user interface, which can help improve the overall visual appeal and user experience of our app.

	Using a `UIVisualEffectView` is fairly straightforward: we simply create an instance of the class, set its `effect` property to an instance of the desired effect, and then add the view to our app's view hierarchy. The visual effect is automatically applied to the views behind the `UIVisualEffectView`, creating a blur effect with subtle highlights and shadows. Here's an example:

	```swift
	let blurEffect = UIBlurEffect(style: .light)
	let blurView = UIVisualEffectView(effect: blurEffect)
	blurView.frame = view.bounds
	view.addSubview(blurView)
	```

	This adds a light blur over the entire screen.
	</details>

- 🟩 [What is the purpose of reuse identifiers for table view cells?](https://www.hackingwithswift.com/interview-questions/what-is-the-purpose-of-reuse-identifiers-for-table-view-cells)
	<details>
		<summary>Answer</summary>
	
	A reuse identifier is a string that uniquely identifies a type of cell in a table view. Its purpose in table view cells (`UITableViewCell`) is to improve performance and memory efficiency by allowing cells to be reused instead of recreated every time they appear on screen. They are also used to distinguish between different types of cells in the same table view (e.g., `PhotoCell` vs. `TextCell`). 

	Although table views can contain thousands of rows, but only a small number are rendered at any given time. Creating a new cell for each row would be memory-intensive, wasteful, and slow. Therefore, each cell is assigned a reuse identifier so that the table view can maintain a reusable pool of cells that can be recycled when they scroll off-screen. When a cell scrolls off-screen and is no longer visible, the table view stores the cell in a reuse queue, indexed by its reuse identifier. When a new cell needs to be displayed on-screen, the table view first checks if there is a reusable cell with the appropriate reuse identifier in the reuse queue. If so, it dequeues the cell from the queue and reconfigures it with new data. If not, it creates a new cell instance.

	Here's an example:

	```swift
	class MyViewController: UIViewController, UITableViewDataSource {

		let tableView = UITableView()

		init() {
			tableView.register(UITableViewCell.self, forCellReuseIdentifier: "MyCell")
		}
 
		func tableView(_ tableView: UITableView, numberOfRowsInSection section: Int) -> Int {
			return 1000
		}
	
		func tableView(_ tableView: UITableView, cellForRowAt indexPath: IndexPath) -> UITableViewCell {
			let cell = tableView.dequeueReusableCell(withIdentifier: "MyCell", for: indexPath)
			cell.textLabel?.text = "Row \(indexPath.row)"
			return cell
		}
	}
	```
	</details>

- 🟩 [When would you choose to use a collection view rather than a table view?](https://www.hackingwithswift.com/interview-questions/when-would-you-choose-to-use-a-collection-view-rather-than-a-table-view)
	<details>
		<summary>Answer</summary>
	
	We would choose a collection view (`UICollectionView`) over a table view (`UITableView`) when more layout flexibility or multidimensional item arrangements are needed, such as grids, custom layouts, or horizontal scrolling.

	Here are some scenarios where a collection view might be preferred over a table view:

	- **Non-linear or custom layouts**: Collection views provide more flexibility in terms of how items are laid out on the screen. They can be arranged in a grid, a carousel, or any other custom layout.
	- **Heterogeneous data types**: While both table and collection views support multiple cell types, collection views are more commonly used for visually rich or diverse layouts (e.g., mixed media like images and text side-by-side).
	- **Interactivity**: Collection views offer greater flexibility for custom interactive elements (like drag-and-drop or complex animations), though both table and collection views support interaction via gestures and delegates.
	- **Horizontal scrolling**: Collection views are designed to handle both vertical and horizontal scrolling, whereas table views are typically used for vertical scrolling only.
	<br />
	
	Overall, a collection view provides more customization options than a table view, making it a good choice when we need a high degree of control over the appearance and behavior of our collection of data.
	</details>

- 🟩 [Which parts of UIKit are you least familiar with?](https://www.hackingwithswift.com/interview-questions/which-parts-of-uikit-are-you-least-familiar-with)
	<details>
		<summary>Answer</summary>
	
	The answer depends on your experience with UIKit. Here are some examples of how I would approach it:

	>- **Core Image**: A framework that provides image processing capabilities. It allows developers to apply a variety of filters to images and manipulate them in various ways.
	>- **UIDocumentInteractionController**: Allows users to share documents with other apps or services. It's useful for apps that need to work with documents of various types, such as PDFs or Word documents
	>- **Core Animation**: Provides a way to create and animate views and other objects on screen. It's a powerful tool for creating complex and dynamic interfaces, but requires a solid understanding of keyframe animations, animation timing, and other related concepts.
	</details>

- 🟧 [How does a view's intrinsic content size aid in Auto Layout?](https://www.hackingwithswift.com/interview-questions/how-does-a-views-intrinsic-content-size-aid-in-auto-layout)
	<details>
		<summary>Answer</summary>
	
	A view's intrinsic content size is its natural size based on its content. It plays a crucial role in Auto Layout. For example, a `UILabel` has an intrinsic content size that matches the dimensions required to display its text, and a `UIButton` uses the size of its title and image.

	When a view provides an intrinsic content size, Auto Layout can often position and size the view **without requiring explicit width or height constraints**. This is especially useful in adaptive layouts, where views need to adjust naturally across different screen sizes and content configurations.

	Here's an example:

	```swift
	let label = UILabel()
	label.text = "Hello, world!"
	stackView.addArrangedSubview(label)
	```

	In this example, we don't need to constraint the label's width or height, as it uses its intrinsic content size, and the stack view arranges it accordingly. Therefore, we don't need to set manual constraints, which is another useful feature.

	Intrinsic content size works together with content hugging and compression resistance priorities to resolve layout conflicts.
	</details>

- 🟧 [What is the function of anchors in Auto Layout?](https://www.hackingwithswift.com/interview-questions/what-is-the-function-of-anchors-in-auto-layout)
	<details>
		<summary>Answer</summary>
	
	In Auto Layout, anchors create constraints that define the position and size of a view relative to other views or the superview. They provide a way to programmatically specify constraints using the layout anchors provided by the `NSLayoutAnchor` class in UIKit in a concise, readable, and type-safe way.

	Each view in UIKit has layout anchors like:
	- `topAnchor`
	- `bottomAnchor`
	- `leadingAnchor`
	- `trailingAnchor`
	- `widthAnchor`
	- `heightAnchor`
	- `centerXAnchor`
	- `centerYAnchor`
	<br>

	These anchors represent specific points or dimensions of the view and can be used to create constraints relative to other views or constant values.

	Here's an example of pinning a view to the edges of its superview:

	```swift
	let box = UIView()
	box.translatesAutoresizingMaskIntoConstraints = false
	view.addSubview(box)
	
	NSLayoutConstraint.activate([
		box.topAnchor.constraint(equalTo: view.topAnchor, constant: 20),
		box.leadingAnchor.constraint(equalTo: view.leadingAnchor, constant: 20),
		box.trailingAnchor.constraint(equalTo: view.trailingAnchor, constant: -20),
		box.bottomAnchor.constraint(equalTo: view.bottomAnchor, constant: -20)
	])
	```

	This example uses anchors to pin `box` inside its superview with padding.
	</details>

- 🟧 [What is the purpose of `@IBDesignable`?](https://www.hackingwithswift.com/interview-questions/what-is-the-purpose-of-ibdesignable)
	<details>
		<summary>Answer</summary>

	`@IBDesignable` is an attribute in Xcode that enables live rendering of custom views directly in Interface Builder without running the app. To use `@IBDesignable`, a custom view can optionally use the `@IBInspectable` attribute to expose specific properties in Interface Builder's Attributes Inspector.

	Here's an example:
	
	```swift
	@IBDesignable
	class MyCustomView: UIView {

		@IBInspectable var cornerRadius: CGFloat = 0 {
			didSet {
				layer.cornerRadius = cornerRadius
				layer.masksToBounds = cornerRadius > 0
			}
		}

		override func prepareForInterfaceBuilder() {
			super.prepareForInterfaceBuilder()
			// Setup code that should run in Interface Builder
		}
	}
	```
	
	In this example:
	- `@IBDesignable` makes the custom view previewable in Interface Builder.
	- `@IBInspectable` makes `cornerRadius` show up in the Attributes Inspector.
	<br>
	</details>

- 🟧 [What is the purpose of `UIMenuController`?](https://www.hackingwithswift.com/interview-questions/what-is-the-purpose-of-uimenucontroller)
	<details>
		<summary>Answer</summary>
	
	`UIMenuController` is a class in UIKit that allows us to display contextual pop-up menu with actions like **Cut**, **Copy**, **Paste**, etc. when a user long-presses or selects editable or selectable content, such as text fields, custom views, or table cells.

	We can add the following actions:
	- Standard system actions (`cut:`, `copy:`, `paste:`).
	- Custom menu items.
	- App-specific logic when a menu item is tapped.
	<br>

	Here's an example of a custom text view with a custom action:

	```swift
	override var canBecomeFirstResponder: Bool {
		return true
	}
	
	override func touchesEnded(_ touches: Set<UITouch>, with event: UIEvent?) {
		becomeFirstResponder()
		
		let menu = UIMenuController.shared
		let custom = UIMenuItem(title: "Highlight", action: #selector(highlightText))
		menu.menuItems = [custom]
		
		menu.showMenu(from: self, rect: bounds)
	}
	
	@objc func highlightText() {
		print("Text highlighted")
	}
	```
	</details>

<p align="right">(<a href="#top">back to top</a>)</p>

---

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Authors

- Questions compiled by: Paul Hudson <[hackingwithswift.com](https://www.hackingwithswift.com/)>
- Questions answered by: HenestrosaDev <[henestrosadev@gmail.com](henestrosadev@gmail.com)>

See also the list of [contributors](https://github.com/HenestrosaDev/ios-interview-questions/contributors) who participated in this project.

## Support

Would you like to support the project? That's very kind of you! However, I would suggest you to consider supporting Hacking with Swift as well for the great compilation of questions! If you still want to support this particular project, you can go to my Ko-Fi profile by clicking on the button down below!

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/U7U5J6COZ)

<p align="right">(<a href="#top">back to top</a>)</p>
