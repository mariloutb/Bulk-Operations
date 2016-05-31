---
layout: post
---

<html lang="en">
	<head>
		<meta charset="utf-8">
		<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
		<meta http-equiv="x-ua-compatible" content="ie=edge">
		<meta name="msvalidate.01" content="89359D9C492A475C0061398008D105FB" />
		
		<!-- seo !-->
		<meta name="description" content="Improve Performance with Bulk Insert, Update, Delete and Merge in SQL and Overcome C# SqlBulkCopy Limitations (SQLServer, SQLAzure, SQLCompact, MySQL, SQLite, .NET, ADO.NET, ASP.NET, C#, CSharp, MVC, MMVC, VB.NET)">
		<meta name="keywords" content="BulkSaveChanges BulkInsert BulkUpdate BulkDelete BulkMerge Insert Update Delete Merge SQLServer SQLAzure SQLCompact MySQL SQLite .NET ADO.NET ASP.NET C# CSharp MVC MMVC VB.NET">
		<title>SQL Bulk Operations | Overcome SqlBulkCopy Limitations with High Performance C# Bulk Insert, Update, Delete and Merge. (SQLServer, SQLAzure, SQLCompact, MySQL, SQLite, .NET, ADO.NET, ASP.NET, C#, CSharp, MVC, MMVC, VB.NET)</title>
		
		<!-- icon/css !-->
		<link rel="icon" type="image/png" href="http://entityframework-plus.net/images/logo.png">
		<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-alpha.2/css/bootstrap.min.css" integrity="sha384-y3tfxAZXuh4HwSYylfB+J125MxIs6mR5FOHamPBG064zB+AFeWH94NdvaCBm8qnd" crossorigin="anonymous">
		<link rel="stylesheet" type="text/css" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.4.0/css/font-awesome.min.css">
		<link rel="stylesheet" type="text/css" href="http://entityframework-plus.net/css/github2.css">
		<!--<link rel="stylesheet" type="text/css" href="http://entityframework-plus.net/css/default.css">!-->
	</head>
	
	<body>
		
		<!-- top-navbar !-->
		<nav id="top-navbar" class="navbar hidden-md-down">
			<div class="container-fluid">
			
				<!-- navbar-nav-product !-->
				<ul class="nav navbar-nav navbar-nav-product">
					<li class="nav-item">
						<a href="#" class="nav-link navbar-toggler collapsed" type="button" data-toggle="collapse" data-target="#top-product"><img src="http://entityframework-plus.net/images/logo.png" height="40" />&nbsp;Products&nbsp;<i class="fa fa-caret-down" aria-hidden="true"></i><i class="fa fa-caret-up" aria-hidden="true"></i></a>
					</li>
				</ul>
				
				<!-- navbar-nav-share !-->				
				<ul class="nav navbar-nav pull-xs-right navbar-nav-share">
					<li class="nav-item">
						<a href="mailto:info@zzzprojects.com"><i class="fa fa-envelope"></i>&nbsp;&nbsp;info@zzzprojects.com</a>
					</li>
					<li class="nav-item">
						<a href="https://www.facebook.com/zzzprojects" target="_blank"><i class="fa fa-facebook"></i></a>
					</li>
					<li class="nav-item">
						<a href="https://twitter.com/zzzprojects" target="_blank"><i class="fa fa-twitter"></i></a>
					</li>
					<li class="nav-item">
						<a href="https://plus.google.com/+Zzzprojects_NetSQL" target="_blank"><i class="fa fa-google-plus"></i></a>
					</li>				
					<li class="nav-item">
						<a href="http://zzzprojects.us9.list-manage.com/subscribe?u=cecbc4775cf67bf1ff82018af&id=4765ffa5f8" target="_blank" class="hidden-xs-down"><i class="fa fa-newspaper-o"></i></a>
					</li>
				</ul>
				
			</div>
		</nav>
		
		<!-- top-product !-->
		<div id="top-product" class="collapse hidden-md-down">
			<div class="container">
				<div class="row">
					<div class="col-lg-3">
						<h3>Entity Framework</h3>
						<ul>
							<li><a href="http://entityframework-extensions.net/" target="_blank">Entity Framework Extensions</a></li>
							<li><a href="http://entityframework-plus.net/" target="_blank">Entity Framework Plus (EF+)</a></li>
						</ul>
					</div>
					<div class="col-lg-3">
						<h3>Bulk Operations</h3>
						<ul>
							<li><a href="http://bulk-operations.net/" target="_blank">Bulk Operations</a></li>
							<li><a href="http://dapper-plus.net/" target="_blank">Dapper Plus</a></li>
						</ul>
					</div>
					<div class="col-lg-3">
						<h3>Expression Evaluator</h3>
						<ul>
							<li><a href="http://eval-expression.net/" target="_blank">Eval Expression.NET</a></li>
							<li><a href="http://eval-sql.net/" target="_blank">Eval SQL.NET</a></li>								
						</ul>
					</div>
					<div class="col-lg-3">
						<h3>Others</h3>
						<ul>
							<li><a href="https://github.com/zzzprojects/Z.ExtensionMethods" target="_blank">Extension Methods</a></li>
							<li><a href="https://github.com/zzzprojects/LINQ-Async" target="_blank">LINQ Async</a></li>
						</ul>
					</div>
				</div>
			</div>	
		</div>

		<!-- menu !-->
		<nav id="menu" class="navbar">
			<div class="container">
				
				<!-- navbar-bar-header !-->
				<ul class="nav navbar-nav navbar-nav-header">
					<li class="nav-item">
						<h1>C# Bulk Operations
						<small>Bulk Insert, Update, Delete, Merge, and More!</small>
						</h1>
					</li>
				</ul>
				
				<!-- navbar-bar-menu !-->
				<ul class="nav navbar-nav pull-xs-right navbar-nav-menu hidden-md-down">
					<li class="nav-item">
						<a class="nav-link" href="https://github.com/zzzprojects/Bulk-Operations/wiki" target="_blank">Wiki</a>
					</li>
					<li class="nav-item">
						<a class="nav-link" href="https://github.com/zzzprojects/Bulk-Operations/issues" target="_blank">Forum</a>
					</li>
					<li class="nav-item">
						<a class="nav-link" href="#pro">PRO Version</a>
					</li>
					<li class="nav-item">
						<a href="https://www.nuget.org/packages/Z.BulkOperations/" target="_blank" class="btn btn-success" role="button" onclick="ga('send', 'event', { eventAction: 'download'});"><span><i class="fa fa-cloud-download"></i>&nbsp;<span>Download</span></span></a>
					</li>
				</ul>
				
				<!-- navbar-bar-menu-mobile !-->
				<ul class="nav navbar-nav pull-xs-right hidden-lg-up navbar-bar-menu-mobile">
					<li class="nav-item">
						<button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#menu-mobile">&#9776;</button>
					</li>
				</ul>
				
			</div>
		</nav>
		
		<div id="menu-mobile" class="collapse hidden-lg-up">
			<div class="container">
				<br />
				<div class="row">
					<div class="col-lg-3">			
						<h3>Menu</h3>
						<ul>
							<li><a class="nav-link" href="https://github.com/zzzprojects/Bulk-Operations/wiki" target="_blank">Wiki</a></li>
							<li><a class="nav-link" href="https://github.com/zzzprojects/Bulk-Operations/issues" target="_blank">Forum</a></li>
							<li><a class="nav-link" href="#pro">PRO Version</a></li>
							<li><a href="https://www.nuget.org/packages/Z.BulkOperations/" target="_blank" class="btn btn-success" role="button" onclick="ga('send', 'event', { eventAction: 'download'});"><span><i class="fa fa-cloud-download"></i>&nbsp;<span>Download</span></span></a></li>
						</ul>
					</div>
					<div class="col-lg-3">
						<h3>Entity Framework</h3>
						<ul>
							<li><a href="http://entityframework-extensions.net/" target="_blank">Entity Framework Extensions</a></li>
							<li><a href="http://entityframework-plus.net/" target="_blank">Entity Framework Plus (EF+)</a></li>
						</ul>
					</div>
					<div class="col-lg-3">
						<h3>Bulk Operations</h3>
						<ul>
							<li><a href="http://bulk-operations.net/" target="_blank">Bulk Operations</a></li>
							<li><a href="http://dapper-plus.net/" target="_blank">Dapper Plus</a></li>
						</ul>
					</div>
					<div class="col-lg-3">
						<h3>Expression Evaluator</h3>
						<ul>
							<li><a href="http://eval-expression.net/" target="_blank">Eval Expression.NET</a></li>
							<li><a href="http://eval-sql.net/" target="_blank">Eval SQL.NET</a></li>								
						</ul>
					</div>
					<div class="col-lg-3">
						<h3>Others</h3>
						<ul>
							<li><a href="https://github.com/zzzprojects/Z.ExtensionMethods" target="_blank">Extension Methods</a></li>
							<li><a href="https://github.com/zzzprojects/LINQ-Async" target="_blank">LINQ Async</a></li>
						</ul>
					</div>
				</div>
			</div>
		</div>
		
		<!-- header !-->
		<header>
			<div class="container">
				<div class="row">
					<div class="col-lg-6">
						<div class="card">
							<div class="card-block">
								<hr class="m-y-md" />
								<h2>Overcome SqlBulkCopy Limitations with hundreds of features</h2>
								<hr class="m-y-md" />
								<div class="lead">
									<a href="https://www.nuget.org/packages/Z.BulkOperations/" target="_blank" class="btn btn-success btn-lg btn-left" role="button" onclick="ga('send', 'event', { eventAction: 'download'});"><span><i class="fa fa-cloud-download fa-2x"></i>&nbsp;<span>Download</span></span></a>
									<br />
									<a href="https://www.nuget.org/packages/Z.BulkOperations/" target="_blank" onclick="ga('send', 'event', { eventAction: 'download'});"><img src="http://entityframework-plus.net/images/nuget/bulk-operations-v.svg" alt="download" /></a>
									<a href="https://www.nuget.org/packages/Z.BulkOperations/" target="_blank" onclick="ga('send', 'event', { eventAction: 'download'});"><img src="http://entityframework-plus.net/images/nuget/bulk-operations-d.svg" alt="" /></a>			
									<div class="text-muted">* PRO Version unlocked for the current month</div>
								</div>
							</div>
						</div>
					</div>
					<div class="col-lg-6">
						<div class="card">
							<br />
							<div class="card-block card-code">
<figure class="highlight"><pre><code data-lang="csharp" class="language-csharp"><span class="c1">// Support all type of operations
</span><span class="n">var</span> <span class="n">bulk</span> <span class="p">=</span> <span class="k">new</span> <span class="nf">BulkOperation</span><span class="p">(</span><span class="n">connection</span><span class="p">);</span>
<span class="n">bulk</span><span class="p">.</span><span class="nf">BulkInsert</span><span class="p">(</span><span class="n">dt</span><span class="p">);</span>
<span class="n">bulk</span><span class="p">.</span><span class="nf">BulkUpdate</span><span class="p">(</span><span class="n">dt</span><span class="p">);</span>
<span class="n">bulk</span><span class="p">.</span><span class="nf">BulkDelete</span><span class="p">(</span><span class="n">dt</span><span class="p">);</span>
<span class="n">bulk</span><span class="p">.</span><span class="nf">BulkMerge</span><span class="p">(</span><span class="n">dt</span><span class="p">);</span>

<span class="c1">// Support List&lt;T&gt; and Lambda Mapping
</span><span class="n">var</span> <span class="n">bulk</span> <span class="p">=</span> <span class="k">new</span> <span class="n">BulkOperation</span><span class="p">&lt;</span><span class="n">Customer</span><span class="p">&gt;(</span><span class="n">connection</span><span class="p">);</span>
<span class="n">bulk</span><span class="p">.</span><span class="n">ColumnInputExpression</span> <span class="p">=</span> <span class="n">c</span> <span class="p">=&gt;</span> <span class="k">new</span> <span class="p">{</span> <span class="n">c</span><span class="p">.</span><span class="n">Name</span><span class="p">,</span>  <span class="n">c</span><span class="p">.</span><span class="n">FirstName</span> <span class="p">};</span>
<span class="n">bulk</span><span class="p">.</span><span class="n">ColumnOutputExpression</span> <span class="p">=</span> <span class="n">c</span> <span class="p">=&gt;</span> <span class="n">c</span><span class="p">.</span><span class="n">CustomerID</span><span class="p">;</span>
<span class="n">bulk</span><span class="p">.</span><span class="n">ColumnPrimaryKeyExpression</span> <span class="p">=</span> <span class="n">c</span> <span class="p">=&gt;</span> <span class="n">c</span><span class="p">.</span><span class="n">Code</span><span class="p">;</span>
<span class="n">bulk</span><span class="p">.</span><span class="nf">BulkMerge</span><span class="p">(</span><span class="n">customers</span><span class="p">);</span></code></pre></figure>
<!--
{% highlight csharp %}
// Support all type of operations
var bulk = new BulkOperation(connection);
bulk.BulkInsert(dt);
bulk.BulkUpdate(dt);
bulk.BulkDelete(dt);
bulk.BulkMerge(dt);

// Support List<T> and Lambda Mapping
var bulk = new BulkOperation<Customer>(connection);
bulk.ColumnInputExpression = c => new { c.Name,  c.FirstName };
bulk.ColumnOutputExpression = c => c.CustomerID;
bulk.ColumnPrimaryKeyExpression = c => c.Code;
bulk.BulkMerge(customers);
{% endhighlight %}!-->
							</div>
						</div>
					</div>
				</div>
			</div>
		</header>
		
		<!-- featured !-->
		<div id="featured">
			<div class="container">
			
				<!-- Improve Performance !-->
				<h2>High <span class="text-bold-red">Performance</span> Operations</h2>
				<div class="row">
					<div class="col-lg-5">
						<p class="featured-tagline">Use <span class="text-bold-red">scalable</span> bulk operations (Bulk Insert, Update, Delete, and Merge) and always get the best <span class="text-bold-red">performance</span> available for your database provider.</p>
						<ul class="featured-list-sm">
							<li>SQL Server 2008+</li>
							<li>SQL Azure</li>
							<li>SQL Compact</li>
							<li>MySQL</li>
							<li>SQLite</li>
							<li>PostgreSQL</li>
							<li>Oracle <i>(Coming soon)</i></li>
						</ul>
						<hr class="m-y-md" />
						<p class="font-weight-bold">Using Entity Framework or Dapper?</p>
						<ul>
							<li><a href="http://entityframework-extensions.net/" target="_blank">Entity Framework Extensions</a></li>
							<li><a href="http://dapper-plus.net/" target="_blank">Dapper Plus</a></li>
						</ul>
					</div>
					<div class="col-lg-7">
						<table class="table table-striped table-hover">
							<tr class="thead-inverse">
								<th>Operations</th>
								<th>1,000 Rows</th>
								<th>10,000 Rows</th>
								<th>100,000 Rows</th>
								<th>1,000,000 Rows</th>
							</tr>
							<tr>
								<th>Insert</th>
								<td>6 ms</td>
								<td>25 ms</td>
								<td>200 ms</td>
								<td>2,000 ms</td>
							</tr>
							<tr>
								<th>Update</th>
								<td>50 ms</td>
								<td>80 ms</td>
								<td>575 ms</td>
								<td>6,500 ms</td>
							</tr>
							<tr>
								<th>Delete</th>
								<td>45 ms</td>
								<td>70 ms</td>
								<td>625 ms</td>
								<td>6,800 ms</td>
							</tr>
							<tr>
								<th>Merge</th>
								<td>65 ms</td>
								<td>160 ms</td>
								<td>1,200 ms</td>
								<td>12,000 ms</td>
							</tr>
						</table>
						
						<p class="text-muted">* Benchmark for SQL Server</p>
					</div>
				</div>
			</div>
		</div>
		
		<!-- testimonials !-->
		<div id="testimonials">
			<div class="container">
				<h2>Amazing <span class="text-bold-red">performance</span>, outstanding <span class="text-bold-red">support</span>!</h2>
				<ul>
					<li>- "We were very, very pleased with the customer support. There was no question, problem or wish that was not answered AND solved within days! We think that’s very unique!" Klemens Stelzmüller, <a href="http://www.beka-software.at/" target="_blank">Beka-software</a></li>
					<li>- "I’d definitely recommend it as it is a great product with a great performance and reliability." Eric Rey, <a href="http://www.transturcarrental.com/" target="_blank">Transtur</a></li>
					<li>- "It’s great. It took me 5 minutes to implement it and makes my application 100x more responsive for certain database operations." Dave Weisberg</li>
				</ul>
				<p><a href="http://www.zzzprojects.com/testimonials/" target="_blank" class="btn btn-primary btn-lg" role="button"><span><i class="fa fa-comments"></i>&nbsp;<span>Read More Success Story</span></span></a></p>
				<br /><br />
				<p><span class="text-bold-red">Share</span> your experience. We love to hear from you: <a href="mailto:info@zzzprojects.com">info@zzzprojects.com</a></p>
			</div>
		</div>
		
		<!-- features !-->
		<div id="feature">
			<div class="container">
				<!-- Output Identity Value !-->
				<a id="output-identity-value" href="#"></a>
				<h2>Output Identity Value</h2>
				<div class="row">
					<div class="col-lg-5">
						<p class="feature-tagline">Overcome SqlBulkCopy limitations and use <span class="text-bold-red">flexible</span> features to output inserted identity and concurrency column values.</p>
					</div>
					<div class="col-lg-7">
{% highlight csharp %}
// Output newly inserted identity value after an insert
bulk.ColumnMappings.Add("CustomerID", ColumnMappingDirectionType.Output);

bulk.BulkInsert(dt);
{% endhighlight %}
					</div>
				</div>

				<hr class="m-y-md" />
				
				<!-- Insert, Update, Delete, Merge and more... !-->
				<a id="insert-update-delete-merge-and-more" href="#"></a>
				<h2>Insert, Update, Delete, Merge and more...</h2>
				<div class="row">
					<div class="col-lg-5">
						<p class="feature-tagline">Bulk Operations is not only about inserting, get more <span class="text-bold-red">capability</span> over SqlBulkCopy.</p>
						<ul>
							<li>BulkInsert</li>
							<li>BulkUpdate</li>
							<li>BulkDelete</li>
							<li>BulkMerge (Upsert)</li>
							<li>BulkSaveChanges</li>
							<li>BulkSynchronize</li>
						</ul>
						
					</div>
					<div class="col-lg-7">
{% highlight csharp %}
// Support all type of operations
var bulk = new BulkOperation(connection);
bulk.BulkInsert(dt);
bulk.BulkUpdate(dt);
bulk.BulkDelete(dt);
bulk.BulkMerge(dt);
bulk.BulkSaveChanges(ds);
bulk.BulkSynchronize(dt);
{% endhighlight %}	
					</div>
				</div>
				
				<hr class="m-y-md" />
				
				<!-- Generic List<> as DataSource !-->
				<a id="generic-list-as-datasource" href="#"></a>
				<h2>Generic List&lt;&gt; as DataSource</h2>
				<div class="row">
					<div class="col-lg-5">
						<p class="feature-tagline">Improve code <span class="text-bold-red">maintainability</span> by using strongly-typed lambda expression over hard coded string.</p>
						<ul>
							<li>Use Bulk Operations with Generic List&lt;&gt;</li>
							<li>Use Bulk Operations with Expando Object</li>
							<li>Use Lambda Expression for mapping</li>
						</ul>
						
					</div>
					<div class="col-lg-7">
{% highlight csharp %}
var bulk= new BulkOperation<Customer>(connection);
bulk.DestinationTableName = "Customer";

// Column Input Expression
bulk.ColumnInputExpression = c => new { c.Code, c.Name };

// Column Output Expression
bulk.ColumnOutputExpression = c => c.CustomerID;

bulk.BulkInsert(customers);
{% endhighlight %}	
					</div>
				</div>
								
				<hr class="m-y-md" />
				
				<!-- Bulk Operations from LINQ Query !-->
				<a id="bulk-operations-from-linq-query" href="#"></a>
				<h2>Bulk Operations from LINQ Query</h2>
				<div class="row">
					<div class="col-lg-5">
						<p class="feature-tagline">Perform bulk operations from LINQ Query without loading entities in memory.</p>
						<ul>
							<li>DeleteFromQuery</li>
							<li>UpdateFromQuery</li>
						</ul>
						
					</div>
					<div class="col-lg-7">
{% highlight csharp %}
var bulk = new BulkOperation<Customer>(connection);

// DELETE all customers inactive for more than 2 years
bulk.DeleteFromQuery(
    c => c.Where(x => x.LastLogin < DateTime.Now.AddYears(-2)));

// UPDATE all customer inactive for more than 2 years
bulk.UpdateFromQuery(
    c => c.Where(x => x.Actif && x.LastLogin < DateTime.Now.AddYears(-2)),
    c => new Customer {Actif = false});
{% endhighlight %}	
					</div>
				</div>
								
				<hr class="m-y-md" />
				
				<!-- AutoMap with Case Insensitive !-->
				<a id="automap-with-case-insensitive" href="#"></a>
				<h2>AutoMap with Case Insensitive</h2>
				<div class="row">
					<div class="col-lg-5">
						<p class="feature-tagline">Sick of not being able to map column because of case sensitivity issue? Use flexible features to customize configuration</p>
						<ul>
							<li>Auditing</li>
							<li>Batch Size</li>
							<li>Case Sensitivity</li>
							<li>Logging</li>
						</ul>
						
					</div>
					<div class="col-lg-7">
{% highlight csharp %}
var bulk = new BulkOperation(connection);
bulk.CaseSensitive = CaseSensitiveType.Insensitive;
bulk.ColumnMappings.Add("cOdE", "Code");
bulk.BulkMerge(dt);
{% endhighlight %}	
					</div>
				</div>
				
				<!-- more-feature !-->
				<p class="more-feature"><a href="https://github.com/zzzprojects/Bulk-Operations/wiki" target="_blank" class="btn btn-primary btn-lg" role="button"><span><i class="fa fa-book"></i>&nbsp;<span>View More Features</span></span></a></p>
				
			</div>
		</div>
		
		<!-- support !-->
		<a id="supports" href="#"></a>
		<div id="support">
			<div class="container">
				<h2>Test our <span class="text-bold-red">Outstanding</span> Support</h2>
				<h3>We usually answer within the next business day, hour, or minutes!</h3>
				<div class="row">
					<hr class="hidden-sm-up" />
					<div class="col-sm-6 col-lg-3">
						<div class="card">
							<div class="card-block">
								<h4 class="card-title">Contact Us</h4>
							</div>
							<a href="mailto:info@zzzprojects.com"><i class="fa fa-users fa-5x"></i></a>
							<div class="card-block">
								<p class="card-text">Email our team for any questions. We love to hear from you!</p>
								<a href="mailto:info@zzzprojects.com">info@zzzprojects.com</a>
							</div>
						</div>
					</div>
					<hr class="hidden-sm-up" />
					<div class="col-sm-6 col-lg-3">
						<div class="card">
							<div class="card-block">
								<h4 class="card-title">Wiki</h4>
							</div>
							<a href="https://github.com/zzzprojects/Bulk-Operations.NET/wiki" target="_blank" onclick="ga('send', 'event', { eventAction: 'github'});"><i class="fa fa-folder-open fa-5x"></i></a>
							<div class="card-block">
								<p class="card-text">Consult our complete documentation to help you getting started.</p>
								<a href="https://github.com/zzzprojects/Bulk-Operations.NET/wiki" target="_blank" onclick="ga('send', 'event', { eventAction: 'github'});">Wiki</a>
							</div>
						</div>
					</div>
					<hr class="hidden-sm-up" />
					<div class="col-sm-6 col-lg-3">
						<div class="card">
							<div class="card-block">
								<h4 class="card-title">Forum</h4>
							</div>
							<a href="https://github.com/zzzprojects/Bulk-Operations.NET/issues" target="_blank" onclick="ga('send', 'event', { eventAction: 'forum'});"><i class="fa fa-weixin fa-5x"></i></a>
							<div class="card-block">
								<p class="card-text">Visit the forum to report issues, ask questions, and propose new features.</p>
								<a href="https://github.com/zzzprojects/Bulk-Operations.NET/issues" target="_blank" onclick="ga('send', 'event', { eventAction: 'forum'});">Forum</a>
							</div>
						</div>
					</div>
					<hr class="hidden-sm-up" />
					<div class="col-sm-6 col-lg-3">
						<div class="card">
							<div class="card-block">
								<h4 class="card-title">Open Source</h4>
							</div>
							<a href="https://github.com/zzzprojects/Bulk-Operations" target="_blank" onclick="ga('send', 'event', { eventAction: 'github'});"><i class="fa fa-github fa-5x"></i></a>
							<div class="card-block">
								<p class="card-text">Access the partial source of the library you're using. (Under development)</p>
								<a href="https://github.com/zzzprojects/Bulk-Operations" target="_blank" onclick="ga('send', 'event', { eventAction: 'github'});">GitHub</a>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
		
		<!-- pricing !-->
		<a id="pro" href="#"></a>
		<div id="pricing">
			<div class="container">
				<div class="row">
					<div class="col-lg-6">
						<h2>Pricing</h2>
						<hr class="m-y-md" />
						<p class="pricing-tagline">Join thousands of projects already using bulk operations  and make <span class="text-bold-red">YOUR</span> customers happy.</p>
						<ul>
							<li>Improve applications responsivity</li>
							<li>Minimize time your customers wait</li>
							<li>Maximize time your customers work</li>
						</ul>
						<p class="pricing-tagline">"Time Is Money" and your customers expect applications to respond as quickly as possible.</p>											
						<hr class="m-y-md" />
						<p>Every month, a <a href="https://www.nuget.org/packages/Z.BulkOperations/" target="_blank" onclick="ga('send', 'event', { eventAction: 'download'});">FREE trial</a> of the PRO version is available to let you evaluate all its features without limitations.</p>
						<hr class="m-y-md" />
						<p class="font-weight-bold">Using Entity Framework or Dapper?</p>
						<ul>
							<li><a href="http://entityframework-extensions.net/" target="_blank">Entity Framework Extensions</a></li>
							<li><a href="http://dapper-plus.net/" target="_blank">Dapper Plus</a></li>
						<ul>
					</div>
					<div class="col-lg-6">
						<table class="table table-hover table-bordered">
							<thead class="thead-inverse">
								<tr>
									<th>Features</th>
									<th>PRO</th>
								</tr>
							</thead>
							<tbody>
								<tr>
									<th>Bulk Insert</th>
									<td><i class="fa fa-check-square-o fa-2x"></i></td>
								</tr>
								<tr>
									<th>Bulk Update</th>
									<td><i class="fa fa-check-square-o fa-2x"></i></td>
								</tr>
								<tr>
									<th>Bulk Delete</th>
									<td><i class="fa fa-check-square-o fa-2x"></i></td>
								</tr>
								<tr>
									<th>Bulk Merge</th>
									<td><i class="fa fa-check-square-o fa-2x"></i></td>
								</tr>
								<tr>
									<th>Bulk SaveChanges</th>
									<td><i class="fa fa-check-square-o fa-2x"></i></td>
								</tr>
								<tr>
									<th>Bulk Synchronize</th>
									<td><i class="fa fa-check-square-o fa-2x"></i></td>
								</tr>
								<tr>
									<th>DeleteFromQuery</th>
									<td><i class="fa fa-check-square-o fa-2x"></i></td>
								</tr>
								<tr>
									<th>UpdateFromQuery</th>
									<td><i class="fa fa-check-square-o fa-2x"></i></td>
								</tr>
								<tr>
									<th>Commercial License</th>
									<td><i class="fa fa-check-square-o fa-2x"></i></td>
								</tr>
								<tr>
									<th>Royalty-Free</th>
									<td><i class="fa fa-check-square-o fa-2x"></i></td>
								</tr>
								<tr>
									<th>Support & Upgrades (1 year)</th>
									<td><i class="fa fa-check-square-o fa-2x"></i></td>
								</tr>
							</tbody>
						</table>
						
						<form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top" onsubmit="return purchase_validate()">
							<input type="hidden" name="cmd" value="_s-xclick">
							<input type="hidden" name="currency_code" value="USD">
							<fieldset class="form-group">
								<input type="hidden" name="on0" value="Seats">
								<select id="provider_type" name="hosted_button_id" class="form-control" onchange="selectProduct()">
									<option value="P4LJES7RRRMRE">SQL Server/ Azure Provider</option>
									<option value="VL4K5FXSRWV88">SQL Compact Provider</option>
									<option value="MVSYAVJHUY9DS">SQLite Provider</option>
									<option value="VEN7DRSDH74YQ">MySQL Provider</option>
									<option value="YZLDF7MB7S66Q">ALL Providers</option>
								</select> 
								<br />
								<select id="product_option" name="os0" class="form-control">
									<option id="seat1" value="1 seat">Bulk Operations $599 (1 seat)</option>
									<option id="seat2_4" value="2-4 seats" selected>Bulk Operations $799 (2-4 seats)</option>
									<option id="seat5_9" value="5-9 seats">Bulk Operations $999 (5-9 seats)</option>
									<option id="seat10_14" value="10-14 seats">Bulk Operations $1199 (10-14 seats)</option>
									<option id="seat15_19" value="15-19 seats">Bulk Operations $1399 (15-19 seats)</option>
								</select> 
							</fieldset>
							<div class="checkbox">
								<label>
									<input id="agree_agreement" type="checkbox">I have read and agree to the <a href="http://www.zzzprojects.com/license-agreement/" target="_blank">License Agreement</a>.
								</label>
							</div>
							<button type="submit" class="btn btn-success btn-lg"><span><i class="fa fa-shopping-cart"></i>&nbsp;<span>BUY NOW</span></span></button>
							<br /><br />
							<p>* Contact us (<a href="mailto:sales@zzzprojects.com">sales@zzzprojects.com</a>) for <span class="text-bold-red">Quote</span>, payment method <span class="text-bold-red">alternative</span>, or major <span class="text-bold-red">bundle discount</span> when purchasing more than one product (or you already bought one).</p>
						</form>				
					</div>
				</div>
			</div>
			
			<!-- validation !-->
			<div id="error_validation" class="modal fade" tabindex="-1" role="dialog" aria-labelledby="modal_agreement" aria-hidden="true">
				<div class="modal-dialog" role="document">
					<div class="modal-content">
						<div class="modal-header">
							<h4 class="modal-title" id="modal_agreement">License Agreement</h4>
						</div>
						<div class="modal-body bg-danger">
							You must read and agree to the License Agreement.
						</div>
						<div class="modal-footer">
							<button type="button" class="btn btn-secondary" data-dismiss="modal">Close</button>
						</div>
					</div>
				</div>
			</div>
		</div>

		<!-- other product !-->
		<div id="product">
			<div class="container">
				<div class="row">
					<div class="col-lg-3">
						<h3>Entity Framework</h3>
						<ul>
							<li><a href="http://entityframework-extensions.net/" target="_blank">Entity Framework Extensions</a></li>
							<li><a href="http://entityframework-plus.net/" target="_blank">Entity Framework Plus (EF+)</a></li>
						</ul>
					</div>
					<div class="col-lg-3">
						<h3>Bulk Operations</h3>
						<ul>
							<li><a href="http://bulk-operations.net/" target="_blank">Bulk Operations</a></li>
							<li><a href="http://dapper-plus.net/" target="_blank">Dapper Plus</a></li>
						</ul>
					</div>
					<div class="col-lg-3">
						<h3>Expression Evaluator</h3>
						<ul>
							<li><a href="http://eval-sql.net/" target="_blank">Eval SQL.NET</a></li>
							<li><a href="http://eval-expression.net/" target="_blank">Eval Expression.NET</a></li>
						</ul>
					</div>
					<div class="col-lg-3">
						<h3>Others</h3>
						<ul>
							<li><a href="https://github.com/zzzprojects/Z.ExtensionMethods" target="_blank">Extension Methods</a></li>
							<li><a href="https://github.com/zzzprojects/LINQ-Async" target="_blank">LINQ Async</a></li>
						</ul>
					</div>
				</div>
			</div>		
		</div>
		
		<!-- footer !-->
		<footer>
			<div class="container text-center-md-down">
				<div class="row">
					<div class="col-lg-6">
						Copyright © <a href="http://www.zzzprojects.com/" target="_blank" class="text-bold">ZZZ Projects Inc.</a> 2014 - 2016
						<div class="hidden-lg-up"></div>
						All rights reserved
					</div>
					<hr class="hidden-lg-up" />
					<div class="col-lg-6 text-right-lg-up social">
						<a href="https://www.facebook.com/zzzprojects" target="_blank"><i class="fa fa-facebook"></i></a>
						<a href="https://twitter.com/zzzprojects" target="_blank"><i class="fa fa-twitter"></i></a>
						<a href="https://plus.google.com/+Zzzprojects_NetSQL" target="_blank"><i class="fa fa-google-plus"></i></a>
						<a href="http://zzzprojects.us9.list-manage.com/subscribe?u=cecbc4775cf67bf1ff82018af&id=4765ffa5f8" target="_blank"><i class="fa fa-newspaper-o"></i></a>
					</div>
				</div>
			</div>
		</footer>

    <script src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.4/jquery.min.js"></script>
    <script src="http://entityframework-plus.net/js/tether.min.js"></script>
	<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-alpha.2/js/bootstrap.min.js" integrity="sha384-vZ2WRJMwsjRMW/8U7i6PWi6AlO1L79snBrmgiDpgIWJ82z8eA5lenwvxbMV1PAh7" crossorigin="anonymous"></script>
	<script type="text/javascript">
	  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
	  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
	  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
	  })(window,document,'script','//www.google-analytics.com/analytics.js','ga');

	  ga('create', 'UA-55584370-7', 'auto');
	  ga('send', 'pageview');
	  
	  function purchase_validate() {
		if($("#agree_agreement").prop('checked')) {
			return true;
		}
		
		$("#error_validation").modal('show')
		return false;
	  }
	  
	  function selectProduct() {
		if($("#provider_type").val() == "YZLDF7MB7S66Q") {
			$("#seat1").html("Bulk Operations $799 (1 developper seat)");
			$("#seat2_4").html("Bulk Operations $999 (2-4 developper seats)");
			$("#seat5_9").html("Bulk Operations $1199 (5-9 developper seats)");
			$("#seat10_14").html("Bulk Operations $1399 (10-14 developper seats)");
			$("#seat15_19").html("Bulk Operations $1599 (15-19 developper seats)");
		}
		else {
			$("#seat1").html("Bulk Operations $599 (1 developper seat)");
			$("#seat2_4").html("Bulk Operations $799 (2-4 developper seats)");
			$("#seat5_9").html("Bulk Operations $999 (5-9 developper seats)");
			$("#seat10_14").html("Bulk Operations $1199 (10-14 developper seats)");
			$("#seat15_19").html("Bulk Operations $1399 (15-19 developper seats)");
		}
	  }
	  
	  selectProduct();
	</script>
	</body>
	
	<style>

/* general */
* {
	 font-family: "Bitter",Georgia,"Times New Roman",serif;
}
.highlight * {
	font-family: Consolas, "Liberation Mono", Menlo, Courier, monospace;
}
.text-bold-red {
	color: #c00;
	font-weight: 700;
}
@media (max-width: 61em) {
	.text-center-md-down {
		text-align: center;
	}
}
@media (max-width: 33em) {
	.text-center-xs-down {
		text-align: center;
	}
}
@media (min-width: 62em) {
	.text-right-lg-up {
		text-align: right;
	}
}

/* top-navbar */
#top-navbar {
	background-color: #000;
	border-bottom: 1px solid #111;
	border-radius: 0px;
}
#top-navbar a {
	color: #fff;
}
#top-navbar a:hover {
	opacity: 0.7;
    transition: all 0.4s ease-in-out 0s;
	text-decoration: none;
}
#top-navbar .navbar-nav-product .fa-caret-down {
	display: none;
}
#top-navbar .navbar-nav-product .collapsed .fa-caret-down {
	display: inline;
}
#top-navbar .navbar-nav-product .fa-caret-up {
	display: inline;
}
#top-navbar .navbar-nav-product .collapsed .fa-caret-up {
	display: none;
}
#top-navbar .navbar-nav-share {
	margin-right: 30px;
	margin-top: 8px;
}
#top-navbar .navbar-nav-share {
	border: 1px solid #999;
}
#top-navbar .navbar-nav-share li {
	border-right: 1px solid #999;
	padding: 0.4rem 1rem;
	margin-left: 0px;
}
#top-navbar .navbar-nav-share li:last-child {
	border-right: 0px;
}


/* top-product */
#top-product {
	border-top: 1px solid #333;
	padding: 20px 0px;
}
#top-product h3 {
	letter-spacing: 1px;
	font-size: 18px;
	font-weight: 700;
}
#top-product ul {
	list-style: none;
	padding-left: 0px;
}
#top-product ul li {
	padding-top: 5px;
}
#top-product a {
	color: #c00;
	font-size: 14px;
	letter-spacing: 0.5px;
}
#top-product a:hover {
	opacity: 0.7;
	text-decoration: none;
    transition: all 0.4s ease-in-out 0s;
}

/* menu */
#menu {
	background-color: #222;
	border-radius: 0px;
	color: #fff;
	border-top: 1px solid #444;
}
#menu .navbar-bar-menu-mobile li {
	font-size: 26px;
}
#menu .navbar-bar-menu-mobile .navbar-toggler {
	font-size: 2rem;
}
#menu .navbar-nav-header {
	padding-left: 20px;
}
#menu .navbar-nav-header small {
	display: block; 
	font-size: 16px;
	margin-top: 5px
}
#menu .navbar-nav-menu {
	font-size: 20px;
	margin-top: 8px;
}
#menu .navbar-nav-menu li {
	padding: 5px 10px;
}
#menu .navbar-nav-menu a {
	color: #fff;
}
#menu .navbar-nav-menu a:hover {
	opacity: 0.7;
    transition: all 0.4s ease-in-out 0s;
}

/* menu-mobile */
#menu-mobile ul {
	list-style: none;
	padding-left: 0px;
}
#menu-mobile ul li {
	padding-top: 5px;
}
#menu-mobile a {
	color: #c00;
	font-size: 14px;
	letter-spacing: 0.5px;
}
#menu-mobile a.btn {
	color: #fff;
}
#menu-mobile a:hover {
	opacity: 0.7;
	text-decoration: none;
    transition: all 0.4s ease-in-out 0s;
}

/* header */
header {
	background: -moz-linear-gradient(to top, #000, #333);
    background: -webkit-linear-gradient(to top, #000, #333);
    background: -ms-linear-gradient(to top, #000, #333);
    background: -o-linear-gradient(to top, #000, #333);
    background: linear-gradient(to top, #000, #333);
	border-top: 1px solid #5d5d5d;
	padding: 40px 0px;
}
header .card {
	background-color: transparent;
	border: none;
	color: #fff;
}
header .card h2 {
	font-size: 2.3rem;
	font-weight: 900;
}
header .card h3 {
	font-size: 1.3rem;
}
header .card hr {
	border-color: initial;
}
header .card .lead .btn {
	width: 175px;
}
header .card .lead .btn-left {
	margin-right: 20px;
}
header .card .lead .btn span {
	display: inline-block;
	height: 40px;
}
header .card .lead .btn span span {
	vertical-align : middle;
}
header .card .lead .text-muted {
	font-size: 14px;
	padding-top: 10px;
}
header .card .card-code {
	background-color: #fff;
	color: #000;
	padding: 0px;
}
@media (max-width: 33em) {
	header .card h1 {
		font-size: 2.5rem;
	}
	header .card .lead .btn {
		margin-bottom: 20px;
	}
}

/* featured */
#featured {
	padding-bottom: 60px;
}
#featured h2 {
	color: #000;
	font-size: 32px;
	font-weight: 700;
	letter-spacing: 0.5px;
	padding-top: 60px;
	padding-bottom: 30px;
}
#featured .featured-tagline {
	font-style: italic;
}
#featured .featured-list-sm ul li {
	font-size: 16px;
	padding: 5px 0;
}
#featured .thead-inverse th {
	background: -moz-linear-gradient(to top, #000, #333);
    background: -webkit-linear-gradient(to top, #000, #333);
    background: -ms-linear-gradient(to top, #000, #333);
    background: -o-linear-gradient(to top, #000, #333);
    background: linear-gradient(to top, #000, #333);
}

/* testimonials */
#testimonials {
    background: -moz-linear-gradient(to top, #ddd, #f2f2f2);
    background: -webkit-linear-gradient(to top, #ddd, #f2f2f2);
    background: -ms-linear-gradient(to top, #ddd, #f2f2f2);
    background: -o-linear-gradient(to top, #ddd, #f2f2f2);
    background: linear-gradient(to top, #ddd, #f2f2f2);
	border-top: 1px solid #ccc;
	padding-bottom: 60px;
}
#testimonials {
	padding: 60px 0px;
	text-align: center;
}
#testimonials ul {
	list-style: none;
	padding: 40px 0px;
}
#testimonials ul li {
	font-style: italic;
	padding: 10px 0;
}

/* feature */
#feature {
	border-bottom: 1px solid #ddd;
    border-top: 1px solid #eee;
	padding-bottom: 60px;
}
#feature h2 {
	color: #000;
	font-size: 32px;
	font-weight: 700;
	letter-spacing: 0.5px;
	padding-top: 60px;
	padding-bottom: 30px;
}
#feature .feature-tagline {
	font-style: italic;
}
#feature ul li {
	font-size: 20px;
	padding-top: 10px;
	padding-bottom: 10px;
}
#feature hr {
	margin-top: 60px;
}
#feature .more-feature {
	margin-top: 90px;
	text-align: center;
}

/* support */
#support {
	background: -moz-linear-gradient(to top, #000, #333);
    background: -webkit-linear-gradient(to top, #000, #333);
    background: -ms-linear-gradient(to top, #000, #333);
    background: -o-linear-gradient(to top, #000, #333);
    background: linear-gradient(to top, #000, #333);
	border-bottom: 1px solid #ddd;
    border-top: 1px solid #eee;
	color: #fff;
	text-align: center;
	padding-top: 60px;
	padding-bottom: 60px;
}
#support h2 {
	font-size: 32px;
	font-weight: 700;
	letter-spacing: 0.5px;
	padding-bottom: 20px;
}
#support h3 {
	font-size: 1.3rem;
	padding-bottom: 40px;
}
#support .card {
	color: #000;
	border: 0.0625rem solid #ccc;
}
#support .card-text {
	min-height: 75px;
}
#support i {
	color: #0275d8;
}

/* pricing */
#pricing {
	background-color: #fefefe;
	padding-top: 60px;
	padding-bottom: 60px;
}
#pricing h2 {
	color: #000;
	font-size: 32px;
	font-weight: 700;
}
#pricing .pricing-tagline {
	font-style: italic;
}
#pricing .table thead th {
	text-align: center;
}
#pricing .table td {
	text-align: center;
}
#pricing .fa-times {
	color: #c9302c;
}
#pricing .fa-check-square-o {
	color: #449D44;
}
#pricing .thead-inverse th {
	background: -moz-linear-gradient(to top, #000, #333);
    background: -webkit-linear-gradient(to top, #000, #333);
    background: -ms-linear-gradient(to top, #000, #333);
    background: -o-linear-gradient(to top, #000, #333);
    background: linear-gradient(to top, #000, #333);
}

/* product */
#product {
	background: -moz-linear-gradient(to top, #000, #333);
    background: -webkit-linear-gradient(to top, #000, #333);
    background: -ms-linear-gradient(to top, #000, #333);
    background: -o-linear-gradient(to top, #000, #333);
    background: linear-gradient(to top, #000, #333);
	border-bottom: 1px solid #5d5d5d;
	color: #fefefe;
	padding: 20px 0px;
}
#product h3 {
	letter-spacing: 1px;
	font-size: 18px;
	font-weight: 700;
}
#product ul {
	list-style: none;
	padding-left: 0px;
}
#product ul li {
	padding-top: 5px;
}
#product a {
	color: #999;
	font-size: 14px;
	letter-spacing: 0.5px;
}
#product a:hover {
	color: #fefefe;
	opacity: 0.7;
	text-decoration: none;
    transition: all 0.4s ease-in-out 0s;
}

/* footer */
footer {
	background: -moz-linear-gradient(top, #333, #222);
    background: -webkit-linear-gradient(top, #333, #222);
    background: -ms-linear-gradient(top, #333, #222);
    background: -o-linear-gradient(top, #333, #222);
    background: linear-gradient(top, #333, #222);
	color: #666;
	padding-top: 5px;
	padding-bottom: 5px;
}
footer a {
	color: #666;
}
footer a:hover {
	color: #666;
	opacity: 0.7;
	text-decoration: none;
    transition: all 0.4s ease-in-out 0s;
}
footer hr {
	border-color: #666;
	margin: 20px;
}
footer .social a {
	font-size: 24px;
	padding: 0px 10px;
}
@media (max-width: 61em) {
  footer {
	padding: 20px 0;
  }
}

</style>
</html>
