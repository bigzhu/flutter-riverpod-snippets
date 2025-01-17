# Flutter Riverpod Snippets

Flutter Riverpod snippets is a way to enhance the way you use Riverpod. It contains a collection of different
snippets such as `provider`.

![greetingProviderGif](gifs/greetingProvider.gif)

## Snippets

| Shortcut                       | Description                                                                 |
| ------------------------------ | --------------------------------------------------------------------------- |
| `consumer`                     | Creates the Consumer widget                                                 |
| `stlessConsumer`               | Creates a ConsumerStateless widget                                          |
| `stfulConsumer`                | Creates a ConsumerStateful widget                                           |
| `stlessHookConsumer`           | Creates a Stateless HookConsumer widget                                     |
| `stfulHookConsumer`            | Creates a Stateful HookConsumer widget                                      |
| `provider`                     | Creates a simple riverod provider                                           |
| `providerFamily`               | Creates a provider with the family modifier                                 |
| `futureProvider`               | Creates a FutureProvider                                                    |
| `futureProviderFamily`         | Creates a FutureProvider with the family modifier                           |
| `streamProvider`               | Creates a StreamProvider                                                    |
| `streamProviderFamily`         | Creates a StreamProvider with the family modifier                           |
| `changeNotifierProvider`       | Creates a ChangeNotifierProvider                                            |
| `changeNotifierProviderFamily` | Creates a ChangeNotifierProvider with the family modifier                   |
| `stateProvider`                | Creates a StateProvider                                                     |
| `stateProviderFamily`          | Creates a StateProvider with the family modifier                            |
| `stateProviderFamily`          | Creates a StateProvider with the family modifier                            |
| `stateNotifierProvider`        | Creates a StateNotifier provider                                            |
| `stateNotifierProviderFamily`  | Creates a StateNotifierProvider with the family modifier                    |
| `stateNotifier`                | Creates a class that extends StateNotifier and allows you to edit the types |
| `listen`                       | Creates a Provider Listenable                                               |

## Contributing
Feel free to open PRs for small issues such as typos. For large issues or features, please open an issue first.

### How to do it
First fork the repo on [GitHub](https://github.com/RobertBrunhage/flutter-riverpod-snippets).
```
git clone <your-forked-repo>

git switch -c my-fix
# fix some code...

git commit -m "Fix typo in readme"
git push origin my-fix
```

The commit naming follows [this structure](https://chris.beams.io/posts/git-commit/)

Add the changes done to `CHANGELOG.md` and update the version in `package.json`

## Release Notes

Please check [Changelog](CHANGELOG.md)
