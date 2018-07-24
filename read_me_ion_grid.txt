
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

'hdens_list.npy' -> log number density
'Z_list.npy'     -> log metallicity
'NH_list.npy'    -> log column density
'G_list.npy'     -> log radiation field
'ion_list.npy'   -> ion list

grid = np.load('ion_column.npy')

grid[i_n,i_z,i_N,i_G,i_ion]  # in cm-2





