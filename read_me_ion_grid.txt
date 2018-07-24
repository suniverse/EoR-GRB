
aux        = {
              'file': ['hdens_list.npy','Z_list.npy','NH_list.npy','intensity_list.npy'],
              'name': ['n_in'          ,'Z_in'      ,'NH_in'      ,'G_in'              ],
              'unit': ['log cm-3'      ,'log zsun'  ,'log cm-2'   ,'log G0'            ]
             }

data_dict  = {
             'ion'     :{ 'data': 'ion_column.npy'
                          ,'list': 'ion_list.npy'
                          ,'unit': 'cm-2'}
             }

'ion_column.npy' -> ion coulmn density for a grid of number density, radiation field, metallicity ,column density, ionname
'linename_list.npy' -> ion list
hdens_list -> log number density
Z_list ->  log metallicity
NH_list -> log column density
G -> log radiation field


