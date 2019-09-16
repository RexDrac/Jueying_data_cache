state-dim: 25
actor-l2-reg: 0.0003
interpolation: False
replay-buffer-size: 1000000
filter-torque: False
filter-action: True
env-id: HumanoidBalanceFilter-v0
loss-output-smooth-coeff: 1.0
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
max-step-num: 2500000000
critic-layer-size: [256, 256]
max-episode-num: 5000000
actor-layer-size: [256, 256]
gating-activation-fn: ['relu', 'relu', 'None']
replay-ratio: 1
Physics-frequency: 1000
squash-action: True
batch-size: 128
max-test-time: 10
loss-entropy-coeff: 0.0
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
record-start-size: 10000.0
actor-weight-decay: 1e-06
expert-index: None
epoch-step-num: 5000000
loss-output-diff-coeff: 0
HLC-frequency: 25
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
expert-num: 4
rollout-step-num: 1
dsr-gait-freq: 1.667
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
task-weight: 0.5
epoch-num: 500
gamma: 0.955
critic-weight-decay: 1e-06
critic-activation-fn: ['relu', 'relu', 'None']
gating-layer-size: [32, 32]
action-dim: 12
train-step-num: 1
total-step-num: 2500000000
bullet-default-PD: False
gating-index: None
dsr-gait-period: 0.6
test-num: 4
critic-lr: 0.0003
max-train-time: 10
replay-start-size: 10000
prioritized-exp-replay: True
loss-output-bound-coeff: 0.0
render-eval: False
imitation-weight: 0.5
joint-interpolation: True
n-step: 1
critic-l2-reg: 0.0003
actor-activation-fn: ['relu', 'relu', 'None']
actor-lr: 0.0003
LLC-frequency: 500
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
max-path-num: 20
max-path-step: 5000
reward-scale: 0.1
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
tau: 0.001
categorical-distribution: {'v_min': -10, 'v_max': 250, 'n_atoms': 51}
