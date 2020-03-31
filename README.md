# Maps
Maps:
HashMaps (Popular)
TreeMaps (Sorted)
LinkedHashMap (Insertion order is kept)

|Key|Value|
|---|---|
|StudentID|Program.Java|
|1234|"public class Program"|


# Methods

# Query Methods

# Real Code example
```java
		List<String> list = Arrays.asList("one", "two", "three");
		List<Integer> integers = Arrays.asList(1,2,3);
		
		Map<String, Integer> map = new HashMap<>();
		
		for(int i = 0; i< list.size();++i) {
			map.put(list.get(i), integers.get(i));
		}
		System.out.println(map);
	}
```
--------------------------------------------------------------------------------
	```java
	duplicate.clear();
		
		if(duplicate.isEmpty()) {
			System.out.println("Duplicate is now officially empty");
		}
		else {
		System.out.println("I must have missed something");
		}
	```	
