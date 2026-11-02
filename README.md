![A northern shore with no lettering: shingle in weathered grey with gull feathers among the stones, the hydrophone cable travelling across the near ground and out into dark water in a slack curve, the hut with one window lit, tarred barrels in a row, the bell still by the door, open water in midnight navy under a low sun laying one bright road of light, and far off on that road the white shoulder of an iceberg](intro-banner.png)

# codeintel-Dead-Code-Finder

![The listening post at work: the tarred hut a third in from the right with one lit window, the hydrophone cable running from its door down the shingle and out into dark water in a long slack curve with one phosphor green glint on its wet length, tarred barrels in a row, a brass bell still by the door, rolled charts under a bench weight, gull feathers motionless on the shingle, an iceberg far over the water, and codeintel-dead-code-finder painted on the hut door as a watch notice](banner.png)

![One hydrophone cable seen from above the waterline: a thick black line entering at the lower left, running out across dark water in one long slack curve, and departing at the upper right, with two rope gold binding bands and one phosphor green glint on the shoreward stretch, and codeintel-dead-code-finder lettered below on a ground ruled as a ship's log line](logo.png)

![The shore in three depths: a low sun holding its one bright road on the water while the iceberg shoulder eases forward by a barely visible degree over a long interval, the hydrophone cable lifting and settling with the swell as the waterline rises and falls against the shingle, and one loose gull feather at the lower edge lifting at its tip, turning once, and settling a hand's breadth from where it lay](scene.svg)


Identifies and reports potentially unused code blocks or variables within a project. Useful for code cleanup and reducing attack surface. - Focused on Tools for static code analysis, vulnerability scanning, and code quality assurance

If any selected tool is missing or fails to run, the run exits 1 and names that tool. An exit 0 run means every selected tool ran.

> **Watch log margin note: an empty section is not a missing tool.** Every tool that ran receives its own headed section in the results even when its output is empty. A missing tool is the failure for which exit 1 and the naming exist.

![Major separator: a rope line tying and untying a sailor's knot across the full rule from left to right, rope gold on midnight navy](sep-heavy.svg)

## Install
`git clone https://github.com/ShadowStrikeHQ/codeintel-dead-code-finder`

> **Watch log margin note: clone line flagged.** The install line above points to ShadowStrikeHQ, not to ShadowGuard-AI. It is preserved as printed and flagged here, not quietly corrected.

![Minor separator: one centred sailor's knot on a rope line with plain rule on either side, rope gold on midnight navy](sep-light.svg)

## Usage
`./codeintel-dead-code-finder [params]`

> **Watch log margin note: usage line flagged.** The usage line above is a placeholder. The parser in main.py accepts a required project path with --dependencies, --output_file, and --ignore after it.

> **Watch log margin note: the required path is missing from the README.** The parameter list below omits project_path, the path to the Python project directory, without which the program refuses to run. It is restored on the website only, marked as restored from the parser.

![Major separator: a rope line tying and untying a sailor's knot across the full rule from left to right, rope gold on midnight navy](sep-heavy.svg)

## Parameters
- `-h`: Show help message and exit
- `--dependencies`: List of dependencies to use for dead code analysis. Options: flake8, pylint, pyre-check.
- `--output_file`: Path to save the results to a file. If not provided, results are printed to the console.
- `--ignore`: No description provided

![Major separator: a rope line tying and untying a sailor's knot across the full rule from left to right, rope gold on midnight navy](sep-heavy.svg)

## License
Copyright (c) ShadowStrikeHQ

> **Watch log margin note: copyright line flagged.** The closing line above reads Copyright (c) ShadowStrikeHQ, preserved as printed. The repository LICENSE file carries the MIT License.
