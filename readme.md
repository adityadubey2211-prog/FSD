localhost - URL
127.0.0.1 - IP address

ctrl+c - stop the server

every request from client has a pair of {request,response}

## npm - node package manager
used to install, run, uninstall any program/project and package
- npm install <packageName>
- npm uninstall <packageName>

to use npm, the project must be npm project,
to create npm projct we can use

- npm init -y
- it creates a package.json file automatically
package.json holds all the information related to install packages from npm
- it also creates a folder node_modules automatically
- node_modules holds the package/library files
- generally we ignore the node_modules by .gitignore
## Status Codes
- 200 -> 0k
- 201 -> created
- 400 -> bad req
- 403 -> forbidden
- 404 -> not found
- 500 ->internal server error


# Content Type

- text/plain
- text/html
- application/json
- text/css

The content type and status code can be send back to client by two ways.

1. res.writeHead
2. res.setHeader
3. res.statusCode
## JSON
1. res.writeHead
2. res.setHeader
3. res.statusCode
server return data only not html context because html content will be written by content devloper. the data is JSON format
JASON always store data in key value pair enclosed by {} array can be [] one pair of {} will represent one obj and its property will be sepreated by , 
```
{id : 1,
name : 'mobile'
price : 25000,
}
```
