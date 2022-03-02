# dollar-pkr
```
Extension to Gnome-Shell in versions (36,38,40,41), for conversion dollar USD in Rs PKR.

# Licence
```
This program is free software: you can redistribute it and/or modify

it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 2 of the License, or
(at your option) any later version.
This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.
You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.
SPDX-License-Identifier: GPL-2.0-or-later
```


# How to install
```
cd /tmp && git clone https://github.com/shoaibzs/dollar-pkr.git && mv dollar-pkr dollar-pkr@shoaibzs.github.com && cp -av dollar-pkr@shoaibzs.github.com ~/.local/share/gnome-shell/extensions/ && gnome-shell-extension-tool --enable-extension dollar-pkr@shoaibzs.github.com && rm -rf dollar-pkr@shoaibzs.github.com
```
To restart GNOME Shell in X11, pressing Alt+F2 to open the Run Dialog and enter restart (or just r). In Wayland Log out and Login agaian.
