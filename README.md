youtube-dl
==========

A downloader for PHP to download best quality youtube video.

##Installation
1. Please unzip 7z file in ffmpeg folder first.  
2. Add new folder then download correspond [ffmpeg](https://www.ffmpeg.org/) if you use other platform(not windows, e.g. MacOSX). ffmpeg must be in folder ffmpeg/{YOUR_OS}/bin/ 
3. Download [wfio](https://github.com/kenjiuno/php-wfio) system to support unicode if you use windows.

##Usage
for basic

	php youtube-dl.php -i {YOUTUBE_ID} -p {SAVE_LOCATION}

for more information 

	php youtube-dl.php -h

or

	php youtube-dl.php -help

##For Windows user
###Web console
I wrote a simple web console for windows users, just click **start.bat** then system will start php server on port 55555 and open Google Chrome.

###Packed bundles
[PHP 5.5.15](http://goo.gl/JWVzm4), extract it to C:\, it include wfio system.   

[ffmpeg](http://goo.gl/OFhRje), extract it to the folder youtube-dl installed in ffmpeg/  


##Copyright / License

Copyright 2014 CapsLock, Studio.

Licensed under the GNU General Public License Version 2.0 (or later); you may not use this work except in compliance with the License. You may obtain a copy of the License in the LICENSE file, or at:

[http://www.gnu.org/licenses/old-licenses/gpl-2.0.txt](http://www.gnu.org/licenses/old-licenses/gpl-2.0.txt)

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.