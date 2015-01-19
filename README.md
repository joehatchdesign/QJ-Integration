# QJ-Integration
Gravity forms, meet Quotation Junction, please play nicely.

This is to set up the InspiredFranking gravity form to API into QJ's database.

See NEW FUNCTION PHP for code to be added to WordPress Theme function.php.

KEY:
$post_url = 'WHERE THE LEAD GOES'

$body = array( aguments:
'affiliate_id' => 'This is the ID for your campaign (provided by QJ'
'category_id' => 'This is the ID for your category (provided by QJ)'

'QJ field_name here' => $entry['number of gforms field']

'send' => '1',
ALWAYS use *'send' => '1',* to disable testing mode

