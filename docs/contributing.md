# Contributing Guide

## Submitting Bugs

**1.** Ensure the bug was not already reported by by reading the [Issues](https://github.com/WikiSpy/WikiSpy/issues).

**2.** Open `/docs/bug_report_template.md` and copy it's contents to the clipboard.

**3.** Create an issue, paste the template into the Issue body and fill it out.

## Feature Requests

**1.** Same as the instructions for submitting a bug report except with using `/docs/feature_request.md`.

### Completing Issues

**1.** Clone the repo and create a branch named after the Issue ticket you're checking in:

```BASH
git clone https://github.com/WikiSpy/WikiSpy.git
cd WikiSpy
git checkout -b Issue123
```

**2.** Complete the issue with passing unit tests and submit the completed issue:

```BASH
git add --all
git commit -m "ModuleID.Add feature XYZ. #123"
git push origin Issue123
```

**3.** Create a Pull Requesting using the `/docs/PULL_REQUEST_TEMPLATE.md`

**4.** Get others to inspect your changes and merge the branch to the master.

**5.** Commit the changes into a branch named after the issue ticket you're mission solves.

```BASH
git branch -m Issue123 Issue125
git add --all
git commit "ModuleID.Fix feature ABC. #125"
git push origin Issue125
```

## License

Copyright © 2021 [Kabuki Starship](https://kabukistarship.com).

This source code form is an open-source document, the Writings and Discoveries, that was written by and contains intellectual property belonging to the IP Owner. The Writings and Discoveries consist of documents, files, source code, technology design files, art, trademarks, and other content contained this file, folder and the GitHub repository, the Repo, located at <https://github.com/WikiSpy/WikiSpy>. The Writings and Discoveries are published under the Kabuki Strong Source-available License, the License, which is a non-commercial open-source license and is for educational and demonstration purposes only. To use the Writings and Discoveries for commercial purposes, you must download the Writings and Discoveries from <https://wikispy.us> and you will be bound to the license agreed upon before downloading the Writings and Discoveries. You may use, reproduce, publicly display, and modify the Writings and Discoveries so long as you submit and donate fixes and derived intellectual property, the Donated Ideas, to the Repo as an Issue ticket to become part of the Writings and Discoveries. You may not sell the Writings and Discoveries or otherwise profit from derivative works created from the Writings and Discoveries without the expressed written permission of the copyright holder. Unless required by applicable law or agreed to in writing, the Writings and Discoveries distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
