#NScanner
##Description
NScanner is a simple .NET desktop application for network scanning. It operates in port scanning or in port sweeping mode, using one of the (currently) three scan methods available. It is developed in C# using WinPcap native libraries and the .NET wrapper, SharpPcap. NScanner provides a basic interface for setting up network scan options with logging capabilities. The NScanner project was initially developed for the "Systems and Network Security" course assignment of Information Systems (MSc) in Athens University of Economics and Business (MScIS 2008-09) by Aggelos Biboudis and Anastasios Nerantzinis.

Modes currently available are Port Sweeping, Port Scanning.
Methods currently available are TCP Scan, UDP Scan, SYN Scan.

##Prerequisites
NScanner utilizes the Windows native libraries of [WinpCap library](http://www.winpcap.org/), a package that is a prerequisite. For the WinpCap API invokation, we have used [SharpPcap](http://sourceforge.net/projects/sharppcap/). SharpPcap is a packet capture framework for the .NET environment, based on pcap / WinPcap libraries. The purpose of this library is to provide an API for capturing, injecting, analyzing and building packets using any .NET language such as C# and VB.NET. The SharpCap project was initiated from [Tamir Gal](http://www.tamirgal.com/blog/page/SharpPcap.aspx) and is currently maintained from Chris Morgan through SourceForge.NET.