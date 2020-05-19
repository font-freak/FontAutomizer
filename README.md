# Font Automizer
A script to automate the creation of Bengali font packages for Magisk and Recovery.
Note that the program does not come with any fonts. You have to obtain and provide the Unicode Bengali fonts by yourself.

## Features
* Can create Bengali font modules for Magisk.
* Can create Bengali font packages for Recovery.

## Newest Release
[v1.0.0](https://github.com/NaeemBolchhi/FontAutomizer/releases)

## Documentation
### Download
[Step-1](data:image/png;base64,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kNhXd7/hXpm/48675N5l98tPdrwow1dGKppv3o0dZiokfpiM93vO916U9Zs2y/nei4H3hq+MyPpNm+XQkWM1L/d6r4ebtwqlIF8sd+f/WTXL5R9mqqE+6op8KqHeE3x84VF5HvsdPxs13Feuubfe2NXfq38+qYR6w339gd8c8qx5dRrTI/F0v6P6od5+gDy1HsJvm5iR/sOfy/ec586v7pSvruuW7719Wfq9V47jhPq52zL0b33lR+M90iMv7XNGi++Rl/sMy+L2HDgvP2otvTZ4Wbb/uPhc9kVru+S//nhA2tv13znRPuA+W37R97vk/xwovTd5Q/7t7V75xrrSe6u75Gs/6pXnD9/wd4dPNdRHDYJXbhMTFy/L9h93y9ecx+R9v0t+74k+ecsd5Z5Qj4iI6Xj803a5cauAKXs8w2FmIdV5PdbDwSPH5I4775IHvvew/OKd92pexnkt/zArDvX/9M8fWXe9/6d//qjmOwKsnXEGyENERETUeby1XW5MFjBlj7dmN8wspDqnHij/JFYc6r06wT1Ol3xcKBav0tsOkIeIiIio81hru4xPFjBlj2U4zCykOqceKP8kphrqDx9v8/2LiIiIiJimx1rbZXyigCmb5TCzkOqceqD8k5hqqEdEREREnE+PtZ6QsYkpTNljrScyG2YWUp1TD5R/Egn1iIiIiJgbPz11Wka+vFHzg/96s5phZqpQkHOfdVLn1EPmzHL5h0moR0RERMTc2N3XL6fOdtZ9uKjXMDM5OSmDg4MyNDRMnVMPmTPL5R8moR4RERERc2V3X78caz2BKXv6zNl599xnnTIwMCiF6RnqnHrIpFkuf5OEekRERERERMScSqhHREREREREzKmEekRERERERMScSqhHREREREREzKmEekRERERERMScSqhHREREREREzKmEekRERERERMScSqhHREREREREzKmEekRERERERMScSqhHREREREREzKmEekRERERERMScSqhHREREREREzKmEekRERERERMScSqhHREREREREzKmEekRERERERMScSqhHREREREREzKmEekRERERERMScSqhHREREREREzKmEekRERERERMScSqhHREREREREzKmEekRERERERMScSqhHREREREREzKmEekRERERERMScSqhHREREREREzKmphPqb+16UK4//Dxn8i/+E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)

## License

    Font Automizer: Automize Bengali Font Packages for Android
    Copyright (C) 2020 NaeemBolchhi

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program. If not, see <http://www.gnu.org/licenses/>.

## Disclaimer

    THERE IS NO WARRANTY FOR THE PROGRAM, TO THE EXTENT PERMITTED BY
    APPLICABLE LAW.  EXCEPT WHEN OTHERWISE STATED IN WRITING THE COPYRIGHT
    HOLDERS AND/OR OTHER PARTIES PROVIDE THE PROGRAM "AS IS" WITHOUT WARRANTY
    OF ANY KIND, EITHER EXPRESSED OR IMPLIED, INCLUDING, BUT NOT LIMITED TO,
    THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR
    PURPOSE.  THE ENTIRE RISK AS TO THE QUALITY AND PERFORMANCE OF THE PROGRAM
    IS WITH YOU.  SHOULD THE PROGRAM PROVE DEFECTIVE, YOU ASSUME THE COST OF
    ALL NECESSARY SERVICING, REPAIR OR CORRECTION.
    
## Agreement

    By downloading and using this program, you hereby agree that you have
    read, understood and accepted the terms as stated in the License.
