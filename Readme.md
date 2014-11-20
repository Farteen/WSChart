Read Me
=====================
**WSChart has been discontinued, and is no longer being maintained. Sorry about that.**

**WSChart's target is using simple code to create charts.**

Charts' screenshots are under the folder /screenshots.
###Pie Chart
![Pie Chart](http://i.minus.com/iblE84WEImIcUS.png)
![Pie Chart](http://i.minus.com/iLvnInh4r7q1O.png)
###Column Chart
![Column Chart](http://i.minus.com/ipVjBxeR2dJDd.png)
![Column Chart](http://i.minus.com/ibgZJVlr64qc9s.png)
![Column Chart](http://i.minus.com/izlQrLobMPr7v.png)
###Line Chart
![Line Chart](http://i.minus.com/iEEX70v8MCOBv.png)
###Combo Chart
![Combo Chart](http://i.minus.com/ibqTtx16VVzGxC.png)
###Area Chart
![Area Chart](http://i.minus.com/ibyiiZCMhgy187.png)
###Scatter Chart
![Scatter Chart](http://i.minus.com/in0540W63Bcf2.png)
###Bar Chart
![Bar Chart](http://i.minus.com/iwBNd7ttFdEQ6.png)

I hope you can use this project to create Pie Chart, Bar Chart, Scatter Chart, Line Chart, Comno Chart, Column Chart, Area Chart.

Usage
------------------
Adding WSChart to your project by:
#### 1 : Add "WSCharts" folder to your project.
#### 2 : Add QuartzCore framework to your project.
#### 3 : Check the demo code in the "ViewController" file to learn how to use it.

#### NOTE : Only WSPieChartWithMotionView supports switch data. Using `- (void)drawChart:(NSArray *)arr withColor:(NSDictionary *)dict` to render the data to chart view. And when you update the view with new data, just pass `arr` and `nil` to it again.

History
----------------------- 
* PieChart : done
* Column Chart : done
* Line Chart : done
* Area Chart : done
* Scatter Chart : done
* Combo Chart : done
* Bar Chart : done

TODO List
-----------------------
* Add "switch data" function to other charts (Only WSPieChartWithMotion supports data updated). 


License
------------------------
WSChart follows MIT license.

Except when otherwise stated (look for LICENSE files in directories or
information at the beginning of each file) all software and
documentation in WSChart project is licensed as follows: 

	Copyright (C) 2012, pyanfield  - pyanfield@gmail.com

	Permission is hereby granted, free of charge, to any person obtaining a copy of
	this software and associated documentation files (the "Software"), to deal in
	the Software without restriction, including without limitation the rights to
	use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies
	of the Software, and to permit persons to whom the Software is furnished to do
	so, subject to the following conditions:

	The above copyright notice and this permission notice shall be included in all
	copies or substantial portions of the Software.

	THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
	IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
	FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
	AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
	LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
	OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
	SOFTWARE.

Other
------------------------
You can contact me with mail 'pyanfield at gmail.com', or follow [@pyanfield](http://weibo.com/pyanfield) on SinaWeibo and [@pyanfield](http://twitter.com/pyanfield) on Twitter.




