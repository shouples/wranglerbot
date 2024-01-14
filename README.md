![](https://cdn.discordapp.com/avatars/411652972955828224/335a79c8f4f37936618110ae535eb2b6.png?size=256)

https://discord.com/developers/applications/

Resources:
- https://discordpy.readthedocs.io/en/stable/intro.html

TODO:
- [ ] switch from ChatCompletion to the Assistants API; each server in its own thread with `channel:username` as the message `name` values
  - [ ] store `channel-username: threadid` mappings locally; if no thread ID exists, create thread and carry over last (up to) 10 messages in history
- [X] load attached images through https://platform.openai.com/docs/guides/vision
- [ ] add function calling for:
  - [X] image generation with https://platform.openai.com/docs/guides/images/usage?context=node
  - [ ] making external API requests
