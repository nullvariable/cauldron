# cauldron
cauldron is a personal social/news aggregator by Doug Cone
Copyright (C) 2015  Doug Cone

# License
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

# About
cauldron is an app designed to be run personally (docker is an excellent choice) to aggregate social media and rss feeds into a single source.
cauldron is designed to learn from your preferences and maximize your time. It will apply a regret value to items based on how you interact with them
and the length of time you spend on them. It will also read your posts and email in order to score keywords that it thinks are important to you. You can
add keywords manually also. If you've spent a week emailing back and forth with coworkers about a new concept, cauldron will learn this and highlight
content in your personal feeds and news that's related.

# Getting started
cauldron is a node.js app and requires a database backend. You can use cauldron right away from the docker image, or you can run the code locally.

# Contributing
Github is the preferred method for bug reporting and accepting patches.