

function get_position_in_ranking($username){
	oci_execute($disp);
	$j=0;

	while($row = oci_fetch_array($disp, OCI_ASSOC+OCI_RETURN_NULLS)){
		
		$i=0;
		$j++;

		foreach ($row as $item){
			if($i==nr-1){
				if($username == $item){
					return $j;
				}
			}
			$i++;
		}
	}
}
