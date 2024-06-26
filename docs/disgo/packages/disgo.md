
```go
import "github.com/disgoorg/disgo"
```

Package disgo is a collection of packages for interaction with the Discord Bot and OAuth2 API. <br>
You can find them in the Navbar below this entry.

## Constants

<a name="Name"></a>

```go
const (
    // Name is the library name
    Name = "disgo"
    // Module is the library module name
    Module = "github.com/disgoorg/disgo"
    // GitHub is a link to the libraries GitHub repository
    GitHub = "https://github.com/disgoorg/disgo"
)
```

## Variables

<a name="Version"></a>

```go
var (
    // Version is the currently used version of DisGo
    Version = getVersion()

    SemVersion = "semver:" + Version

    // OS is the currently used OS
    OS  = getOS()
)
```

<a name="New"></a>
## func [New](<https://github.com/disgoorg/disgo/blob/master/disgo.go#L100>)

```go
func New(token string, opts ...bot.ConfigOpt) (bot.Client, error)
```

New creates a new bot.Client with the provided token & bot.ConfigOpt\(s\)


