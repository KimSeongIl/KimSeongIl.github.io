---
layout: default
title: Skills
permalink: /skills/
navigation: Skills
program_languages : ["JSP (Spring)", "PHP (Codeigniter)", "Android", "Html / CSS (Bootstrap) / JavaScript (jQuery)", "AngularJS"]
program_ability : [0, 90, 90, 80, 80, 30]
database : ["MySQL", "PostgreSQL", "Oracle", "SQL-Server"]
database_ability : [0, 90, 60, 40, 50]
---

# {{ page.title }}
---

<br>

<h3 class="section">Programming</h3>

<div class="row hidden-xs">
	<div class="col-sm-10 col-sm-offset-1">
		<table class="table small" style="margin-top: 40px; margin-bottom: 40px;">
			<thead>
				<tr>
					<td class="col-sm-2"></td>
					<td class="col-sm-2 text-center" style="vertical-align: middle;">Unfamiliar</td>
					<td class="col-sm-2 text-center" style="vertical-align: middle;">Learning</td>
					<td class="col-sm-2 text-center" style="vertical-align: middle;">Understood</td>
					<td class="col-sm-2 text-center" style="vertical-align: middle;">Used in Projects</td>
					<td class="col-sm-2 text-center" style="vertical-align: middle;">Experienced</td>
				</tr>
			</thead>
			<tbody>
				{% for node in page.program_languages %}
				<tr>
					<td class="col-sm-2">{{ node }}</td>
					<td colspan="5" class="col-sm-10">
						<div class="progress">
							<div class="progress-bar" role="progressbar" aria-valuemax="100" style="width: {{page.program_ability[forloop.index]}}%; height: 60px;">
							</div>
						</div>
					</td>
				</tr>
				{% endfor %}
			</tbody>
		</table>
	</div>
</div>

<!-- Moblie -->
<div class="visible-xs">
	<table class="table small">
		<thead>
			<tr>
				<td>JSP (Spring)</td>
				<td>
					<i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star-half-o"></i>
					(Experienced)
				</td>
			</tr>
		</thead>
		<tbody>	
			<tr>
				<td>PHP (Codeigniter)</td>
				<td>
					<i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star-o"></i>
					(Used in Projects)
				</td>
			</tr>
			<tr>
				<td>Android</td>
				<td>
					<i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star-half-o"></i>
					(Experienced)
				</td>
			</tr>
			<tr>
				<td>Html / CSS (Bootstrap) / JavaScript (jQuery)</td>
				<td>
					<i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star-o"></i>
					(Used in Projects)
				</td>
			</tr>
			<tr>
				<td>AngularJS</td>
				<td>
					<i class="fa fa-star"></i><i class="fa fa-star-half-o"></i><i class="fa fa-star-o"></i><i class="fa fa-star-o"></i><i class="fa fa-star-o"></i>
					(Learning)
				</td>
			</tr>
		</tbody>
	</table>
</div>

<br>

<h3 class="section">Datebase</h3>

<div class="row hidden-xs">
	<div class="col-sm-10 col-sm-offset-1">
		<table class="table small" style="margin-top: 40px; margin-bottom: 40px;">
			<thead>
				<tr>
					<td class="col-sm-2"></td>
					<td class="col-sm-2 text-center" style="vertical-align: middle;">Unfamiliar</td>
					<td class="col-sm-2 text-center" style="vertical-align: middle;">Learning</td>
					<td class="col-sm-2 text-center" style="vertical-align: middle;">Understood</td>
					<td class="col-sm-2 text-center" style="vertical-align: middle;">Used in Projects</td>
					<td class="col-sm-2 text-center" style="vertical-align: middle;">Experienced</td>
				</tr>
			</thead>
			<tbody>
			{% for node in page.database %}
				<tr>
					<td class="col-sm-2">{{ node }}</td>
					<td colspan="5" class="col-sm-10">
						<div class="progress">
							<div class="progress-bar-danger" role="progressbar" aria-valuemax="100" style="width: {{page.database_ability[forloop.index]}}%; height: 60px;">
							</div>
						</div>
					</td>
				</tr>
				{% endfor %}
			</tbody>
		</table>
	</div>
</div>

<!-- Moblie -->
<div class="visible-xs">
	<table class="table small">
		<thead>
			<tr>
				<td>MySQL</td>
				<td>
					<i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
					(Experienced)
				</td>
			</tr>
		</thead>
		<tbody>
			<tr>
				<td>PostgreSQL</td>
				<td>
					<i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star-o"></i><i class="fa fa-star-o"></i>
					(Understood)
				</td>
			</tr>
			<tr>
				<td>Oracle</td>
				<td>
					<i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star-o"></i><i class="fa fa-star-o"></i><i class="fa fa-star-o"></i>
					(Learning)
				</td>
			</tr>
			<tr>
				<td>SQL- Server</td>
				<td>
					<i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star-o"></i><i class="fa fa-star-o"></i><i class="fa fa-star-o"></i>
					(Learning)
				</td>
			</tr>
		</tbody>
	</table>
</div>