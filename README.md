# untildify
Utility to replace ~ with user home directory

## Example

```rust
extern crate untildify;

fn main() {
  println!("Untildify : {}", untildify::untildify("~/Desktop"));
  // prints /Users/<user_name>/Desktop
  
  // Other Examples
  // assert_eq!(untildify("~/a/b/c/d/e"), "/User/Untildify/a/b/c/d/e");
  // assert_eq!(untildify("~/"), "/User/Untildify/");
}

```