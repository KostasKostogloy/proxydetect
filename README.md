proxydetect
===========
    Copyright (C) 2013 by Jan Helbling <jan.helbling@gmail.com>
    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.



It checks the HTTP header to traces of proxys, scans short 4 ports, to check whether it is a server, and compares a list of default proxy ports with $ _SERVER ["REMOTE_PORT"].

functions:
	bool check_if_proxy()
		-- returns true if the visitor is using a proxy.
		-- returns false if the visitor isn't using a proxy.
