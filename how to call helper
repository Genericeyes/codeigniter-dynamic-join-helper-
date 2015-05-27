
//add helper
  $this->load->helper('joins_helper');

    $where                  =  array( ); 
    $group                  =  '*';

    $joinsArray = array(
        array('table'=>'table','tableJoin'=>'table1.tableId=table1.tableId'),
        array('table'=>'table','tableJoin'=>'table1.tableId=table1.tableId')
        );
                
   $result_set             = joins('*','table1','result',$joinsArray,$where,$group);
