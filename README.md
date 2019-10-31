# Xcode Snippets

Here are some of my personal Xcode snippets that I use in development. I'll be updating this list as I go, and would definitely appreciate any additions/modifications to simplify some of the tedious things we write in Xcode.

### Snippets
`paro` == `@property (nonatomic, assign, readonly) `

`parw` == `@property (nonatomic, assign, readwrite) `

`pcro` == `@property (nonatomic, copy, readonly) `

`pcrw` == `@property (nonatomic, copy, readwrite) `

`psro` == `@property (nonatomic, strong, readonly) `

`psrw` == `@property (nonatomic, strong, readwrite) `

`unavailable` == `__attribute__((unavailable("Please use `...`.")));`

`weakify` == `__weak typeof(self)weakSelf = self;`

`strongify` == `__strong typeof(weakSelf)strongSelf = weakSelf;`


### How to Install
To install, simply move the snippets to your `~/Library/Developer/Xcode/UserData/CodeSnippets` folder. Create the folder if it doesn't exist.
