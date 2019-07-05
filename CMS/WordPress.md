Personnalisation CSS additionnel (code d'un projet réalisé)

td:last-child a
{
	opacity:0;
	position: absolute;
	z-index:10;
}
tr:nth-child(even)
{
	background-color: #f2f2f2;
}
tr:nth-child(odd)
{
	background-color: white;
}
tbody tr:hover
{
	background-color: orange;
}
td
{
	border:0;
}
.events-table td, .events-table th
{
	border-color: #f2f2f2;
}
.entry-content i
{
	display: none;
}
@media (max-width: 576px)
{
	  .wpcf7-form-control-wrap input
    {
	    width: 260px;	
    }
}
