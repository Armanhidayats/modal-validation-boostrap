# modal-validation-boostrap
disini membuat modal form dengan wajib mengisi setiap data





    <div class="main-panel">
        <div class="content-wrapper">
            
          <div class="row">
            <div class="col-lg-7 grid-margin stretch-card">
              <div class="card">
                <div class="card-body">
                  <h4 class="card-title">Atlet</h4>
                  <p class="card-description">
                    Data seluruh Atlet
                  </p>
                    <nav class="navbar navbar-light bg-light">
                    <button type="button" class="btn btn-primary my-4" data-toggle="modal" data-target=".bd-example-modal-lg">Tambahkan Atlet</button>

<div class="modal fade bd-example-modal-lg" tabindex="-1" role="dialog" aria-labelledby="myLargeModalLabel" aria-hidden="true">
  <div class="modal-dialog modal-lg">
  <div class="container">
    <div class="modal-content ">
    <div class="modal-body">
      <h5>Data Atlet</h5>
    <form class="forms-sample">
                    <div class="form-group">
                    <label for="validationDefault01">No.Atlet</label>
                    <input type="number" class="form-control" id="validationnoatlet" placeholder="No.Atlet"  required>
                    </div>
                    <div class="form-group">
                    <label for="validationDefault">Nama</label>
                      <input type="text" class="form-control" id="validationNama" placeholder="Nama"  required>
                    </div>
                    <div class="form-group">
                    <label for="validationDefault01">Tanggal lahir</label>
                   <input type="datepicker" class="form-control" id="validation" placeholder="Tanggal lahir" required>
                    </div>

                    <div class="form-group">
                    <label for="validationDefault">Gender</label>
                              <select class="form-control" required aria-label="select example">
                              <option value="">--Pilih Gender--</option>
                              <option value="1">Laki-Laki</option>
                              <option value="2">Perempuan</option>
                             
                            </select>
                            <div class="invalid-feedback">Example invalid select feedback</div>
                      </div>
                    
                      <div class="form-group">
                      <label for="exampleSelectGender">Bidang</label>
                        <select class="form-control" required arial-label="select example">
                          <option value="">Pembinaan Prestasi</option>
                          <option value="1">Penelitian dan Pengembangan</option>
                          <option value="2">Organisasi</option>
                          <option value="3">Pengumpulan dan Pengelolaan Data</option>
                          <option value="4">Pendidikan dan Penataran</option>
                          <option value="5">Pengumpulan dan Pengelolaan Data</option>
                          <option value="6">Perencanaan Program & Anggaran dan Usaha</option>
                          <option value="7">Mobilisasi Sumber Daya</option>
                          <option value="8">Kesejahteraan Pelaku Olahraga</option>
                          <option value="9">Media dan Humas</option>
                          <option value="10">Kerjasama Dalam Negri dan Antar Lembaga</option>
                          <option value="11">Umum dan Pengelolaan Asset</option>
                          <option value="12">Pembinaan Hukum Olahraga dan Pengawasan</option>
                        </select>
                        <div class="invalid-feedback">Example invalid select feedback</div>
                      </div>


                      <div class="form-group">
                      <label for="exampleTextarea1">Alamat</label>
                      <textarea class="form-control" id="validation" rows="4" required></textarea>
                    </div>

                    <button type="submit" class="btn btn-primary mr-2">Submit</button>

                    <a  href="<?=Base_url('Atlet/Atlet');?>" class="btn btn-light">Cancel</a>
                  </form>
      </div>
    </div>
  </div>
</div>
  </div>
  
                        <form class="form-inline">
                            <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
                            <button class="btn btn-outline-success my-4 my-sm-2" type="submit">Search</button> 
                          
                        </form>

                        </nav>  
                  <div class="table-responsive">
                    <table class="table table-striped">
                      <thead>
                        <tr>
                          <th>
                            No.Atlet
                          </th>
                          <th>
                            Nama
                          </th>
                          <th>
                            Tanggal Lahir
                          </th>
                          <th>
                            Alamat
                          </th>
                          <th>
                            Domisili
                          </th>
                          <th>
                            Event lomba (PON,POPNAS,kEJURNAS)
                          </th>
                          <th>
                            Prestasi
                          </th>
                        </tr>
                      </thead>
                      <tbody>
                        <tr>
                          <td class="py-1">
                            <img src="../../images/faces/face1.jpg" alt="image"/>
                          </td>
                          <td>
                            Herman Beckssadadwdaw
                          </td>
                          <td>
                            dwwadwadwadawdawdawdwa
                          </td>
                          <td>
                            May 15, 2015wadwadawdawwadwadawdawdawdawdwa
                          </td>
                          <td>
                            May 15, 2015wadwadawdawwadwadawdawdawdawdwa
                          </td>
                          <td>
                            May 15, 2015wadwadawdawwadwadawdawdawdawdwa
                          </td>
                          <td>
                            May 15, 2015wadwadawdawwadwadawdawdawdawdwa
                          </td>
                          <td>
                          <button class="btn btn-outline-success " type="submit">Edit Atlet</button>
                          &emsp;
                          <button class="btn btn-outline-success " type="submit">Hapus</button>
                          </td>
                        </tr>
                       
                      </tbody>
                    </table>
                  </div>
                </div>
                
              </div>
            </div>

            <div class="col grid-margin">
              <div class="card">
                <div class="card-body">
                  <h5 class="card-title">Cara daftar Akun koni </h5>
                  <p class="card-description">
                    Harus di isi dengan akun gmail yang aktif.....
                  </p>
                 
             <h5> 1.Isi data sesuai dengan indentitas anda</h5>
             <br>
              <h5> 2.Masukan Akun Gmail yang aktif</h5>
            <br>
              <h5> 3.Setelah menekan tombol submit maka secara otomatis ada notifikasi di gmail untuk aktivasi</h5>
              <br>
              <h5> 4.Dan setelah aktivasi Akun bisa digunakan</h5>
              <br>
              <h5> 5.Refresh halaman dan selamat akun ada sudah bisa masuk</h5>

 
            </div>                 
                </div>
    </div>

    </div>
    
