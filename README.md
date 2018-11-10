# Raw Grid-system

* col-1{ width:8.33% }
* col-2{ width:16.66% }
* col-3{ width:25% }
* col-4{ width:33.33% }
* col-5{ width:41.66% }
* col-6{ width:50% }
* col-7{ width:58.33% }
* col-8{ width:66.66% }
* col-9{width:75% }
* col-10{ width:83.33% }
* col-11{ width:91.66% }
* col-12{ width:100% }


>  [class*='col-']{
 	float: left;
 	box-sizing: border-box;
 	border: 1px solid;
 }


> .wrapper{
	width: 80%;
	margin: 0 auto;
	height: auto;
}

> .row::after{
	content: '';
	clear: both;
	display: block;
}
