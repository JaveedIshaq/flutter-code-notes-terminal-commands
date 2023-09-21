### flutter riverpod dependencies

`
flutter pub add flutter_riverpod riverpod_annotation
`
### dev dependencies
`
flutter pub add --dev build_runner custom_lint riverpod_generator riverpod_lint
`

### for Error Don't use 'BuildContext's across async gaps. Try rewriting the code to not reference the 'BuildContext'.

`
 if (context.mounted) {
     // Your Code here
 }
`
