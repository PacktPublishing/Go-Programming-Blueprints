# Go Programming Blueprints - Second Edition
This is the code repository for [Go Programming Blueprints - Second Edition](https://www.packtpub.com/application-development/go-programming-blueprints-second-edition?utm_source=github&utm_campaign=9781786468949&utm_medium=repository), published by Packt. It contains all the supporting project files necessary to work through the book from start to finish.

## Instructions and Navigation
All of the code is organized into folders. Each folder starts with number followed by the application name. For example, Chapter02.

You will see code something similar to the following:

```
import (
	"github.com/gorilla/websocket"
)

// client represents a single chatting user.
type client struct {

	// socket is the web socket for this client.
	socket *websocket.Conn

	// send is a channel on which messages are sent.
	send chan []byte

	// room is the room this client is chatting in.
	room *room
}

```

### Software and Hardware List

| Chapter  | Software required | OS required            |
| -------- | ------------------| ------------           |
| 1 to 11  | Go 1.7            | Windows/Mac/Ubuntu     |

## Related Go Products:
* [Go: Building Web Applications](https://www.packtpub.com/application-development/go-building-web-applications?utm_source=github&utm_campaign=9781787123496&utm_medium=repository)
* [Go Programming Blueprints](https://www.packtpub.com/application-development/go-programming-blueprints?utm_source=github&utm_campaign=9781783988020&utm_medium=repository)
* [Mastering Go Web Services](https://www.packtpub.com/web-development/mastering-go-web-services?utm_source=github&utm_campaign=9781783981304&utm_medium=repository)






### Suggestions and Feedback
[Click here](https://docs.google.com/forms/d/e/1FAIpQLSe5qwunkGf6PUvzPirPDtuy1Du5Rlzew23UBp2S-P3wB-GcwQ/viewform) if you have any feedback or suggestions.
