# SRP OTP
www.srp.tohoku.ac.jp の認証時に用いられるOTP(ワンタイムパスワード)を生成するためのライブラリのJava実装です．
使い方についてはSRPClientを御覧ください．

## LICENSE
SRP OTP is licensed under the terms of the [GNU General Public License](https://www.gnu.org/copyleft/gpl.html), with the "library exception" which permits its use as a library in conjunction with non-Free software:
> "As a special exception, the copyright holders of this library give you permission to link this library with independent modules to produce an executable, regardless of the license terms of these independent modules, and to copy and distribute the resulting executable under terms of your choice, provided that you also meet, for each linked independent module, the terms and conditions of the license of that module. An independent module is a module which is not derived from or based on this library. If you modify this library, you may extend this exception to your version of the library, but you are not obligated to do so. If you do not wish to do so, delete this exception statement from your version."

The effect of that license is similar to using the LGPL, except that static linking is permitted. GPL with that exception is sometimes called the Guile License, because the Guile implementation of Scheme (for embedding) uses this license.

このライブラリにはGPLライセンス下で提供されているgnu-cryptoを含みます．