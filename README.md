# language-cmake package (`language-cmake-2`)

Syntax highlighting for CMake in atom. Converted from the
[Textmate bundle](https://github.com/textmate/cmake.tmbundle)

---

## __9/9/2020:__ Original [`lucas-clemente/language-cmake`](https://github.com/lucas-clemente/language-cmake) repository discontinued?
The original [lucas-clemente/language-cmake](https://github.com/lucas-clemente/language-cmake) repository has been archived. Because it's maintainer has [already told](https://github.com/lucas-clemente/language-cmake/pull/23#issuecomment-493762702) that he does not use Atom editor anymore and the last commit is [my merged pull request](https://github.com/lucas-clemente/language-cmake/pull/24) from more than a year ago (version 1.2.0), _the project seems discontinued to me_.

A couple of days ago, I made [another pull request (#25)](https://github.com/lucas-clemente/language-cmake/pull/25), once again updating the list of keywords based on the changes in [CMake](https://cmake.org/cmake/help/v3.18/) over the past year. It's possible that this new pull request will never be merged. So I decided to use my forked repository [TrinityCoder/language-cmake](https://github.com/TrinityCoder/language-cmake), more specifically the `devel` branch (newly set as default), to provide my current up-to-date version of the `language-cmake` package. __I don't have access to the official repo nor to the [Atom.io language-cmake package administration](https://atom.io/packages/language-cmake).__

-- [TrinityCoder](https://github.com/TrinityCoder) (9/9/2020)

---

## __30/11/2020:__ Rename to `language-cmake-2` and update of [`package.json`][1] config
I have decided to rename this fork to `language-cmake-2` so the name is clearly
different from the original. This change only happened in the package config
(in [`package.json`][1]), the Github repository will not be renamed.

Package name is different but versioning continues as before without any change.

## __30/11/2020:__ How to get this version into Atom?
First, you should disable the original `language-cmake` package, so these two
do not interfere.

```sh
apm install https://github.com/TrinityCoder/language-cmake.git
```

That's all; `language-cmake-2` is installed in your Atom editor, you can find it in
Settings -> Packages -> Git Packages.

[1]: package.json
