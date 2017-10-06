# Lite CSS

*,*:after,*:before {
	margin: 0;
	padding: 0;
	box-sizing: border-box;
}

body {
	font: 100% arial;
	line-height: 1.5;
}

.row {
	clear: both;
	overflow: auto;
	margin: 0 auto;
	max-width: 1000px;
}

.gut {
	padding: 0 10px;
}

.col-1 {
	float: left;
	width: 100%;
}

.col-2 {
	float: left;
	width: 50%;
}

.col-3 {
	float: left;
	width: 33.33333%;
}

.col-4 {
	float: left;
	width: 25%;
}

.content {
	float: left;
	width: 70%;
}

.sidebar {
	float: left;
	width: 30%;
}

.center {
	text-align: center;
}

@media (max-width: 768px) {
	.col-1,.col-2,.col-3,.col-4,.content,.sidebar,th,td {
		float: none;
		width: 100%;
		display: block;
	}
}
