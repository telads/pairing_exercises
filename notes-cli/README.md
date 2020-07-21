### Task

Write a simple notes app that you can run from your command line and that writes the notes to a file.

### Acceptance Criteria

_NB: If you're at the beginning of the course, this exercise is meant to be spiked in pairs, not test-driven. If you're coming back to this exercise - test-drive it!_

From your project directory, start the app. It displays a prompt.
```sh
$ ruby app.rb
Welcome to Notes CLI!
>
```

Enter text after the prompt. Hit enter to store your note and get another prompt.

```sh
$ ruby app.rb
Welcome to Notes CLI!
> Ruby is a great language!
> Writing apps is fun :)
>
```

You should see the following in a separate text file called `notes.txt`

```
Ruby is a great language!
Writing apps is fun :)
```

When you've finished writing notes, you can exit the program using `exit` and be shown a message.

```sh
$ ruby app.rb
Welcome to Notes CLI!
> Ruby is a great language!
> Writing apps is fun :)
> exit
Goodbye!
```

For further requirements, see your coach.
